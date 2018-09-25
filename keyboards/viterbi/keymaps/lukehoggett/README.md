Build only 

make viterbi/rev1:lukehoggett

Build and flash

make viterbi/rev1:lukehoggett:avrdude


docker run -e keymap=lukehoggett -e keyboard=viterbi/rev1 --rm -v $('pwd'):/qmk:rw edasque/qmk_firmware
