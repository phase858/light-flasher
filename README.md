# light-flasher
A ruby script to flash arbitary lights in morse code with sysfs. (only works on linux)
## setup and usage
- download ``flasher.rb`` and ``sudo chomod +x flasher.rb``
- find the ``brightness`` file of the light you want to flash in ``/sys/class/``
- edit ``@light`` to your chosen lights brightness file
- to use the script: ``sudo ./flasher.rb your text here``
- change ``@loop`` to ``true`` to enable loop mode
- while in loop mode press q then enter to quit gracefully
- other config options such as brightness level and blink duration are labeled in the script
