# libarduino

## Overview

Libarduino is a quick and dirty reimplementation of some parts of the arduino
library. The initial goal was to reuse the existing code base of the early
prototype for the car, which was based on an arduino board.  
Now, that this need isn't here anymore, this library will soon be removed and
replaced by more specific implementations.

## Features

Only a reduced subset of the arduino library is implemented :

* GPIO readind and writing
* analogWrite()
* input and output via the "serial" port, emulated through the standard input
  and output. Only one serial port emulation is available.
* servo control

### For this README.md file

    This file is part of the Carino project documentation.
    Copyright (C) 2015
      Nicolas CARRIER <carrier dot nicolas0 at gmail dot com>
    See the file doc/README.md for copying conditions

