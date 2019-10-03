# light-flasher
A hacky and semi shitty probably ruby script to flash arbitary lights in morse code. (only works on linux)
## setup and usage
- download ``flasher.rb`` and ``sudo chomod +x flasher.rb``
- find the ``brightness`` file of the light you want to flash in ``/sys/class/``
- edit ``@light`` to you chosen lights brightness file
- to use the script: ``sudo ./flasher.rb your text here``
- other config options such as brightness level and blink duration are labeled in the script
