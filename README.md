# g810-led

Linux LED controller for the Logitech G810 Keyboard

Compatible with the Logitech G410 and G610 Keyboard (look at the wiki : https://github.com/MatMoul/g810-led/wiki)

![jj](https://raw.githubusercontent.com/MatMoul/g810-led/master/pictures/logitech_g810-2.jpg)

Install and use :</br>
- look at the wiki : https://github.com/MatMoul/g810-led/wiki

Samples :</br>
`g810-led -p /etc/g810/profile # Set a profile`</br>
`g810-led -k logo ff0000 # Set color of a key`</br>
`g810-led -a 00ff00 # Set color of all keys`</br>
`g810-led -g fkeys ff00ff # Set color of a group of keys`</br>
`g810-led -s color # Set keyboard power on effect`</br>

Samples with no commit :</br>
`g810-led -an 000000 # Set color of all key with no action`</br>
`g810-led -gn modifiers ff0000 # Set color of a group with no action`</br>
`g810-led -kn w ff0000 # Set color of a key with no action`</br>
`g810-led -kn a ff0000 # Set color of a key with no action`</br>
`g810-led -kn s ff0000 # Set color of a key with no action`</br>
`g810-led -kn d ff0000 # Set color of a key with no action`</br>
`g810-led -c # Commit all changes`</br>
