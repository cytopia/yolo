```
  __  __    _____    __       _____    
/\  /\  /\ ) ___ (  /\_\     ) ___ (   
\ \ \/ / // /\_/\ \( ( (    / /\_/\ \  
 \ \__/ // /_/ (_\ \\ \_\  / /_/ (_\ \ 
  \__/ / \ \ )_/ / // / /__\ \ )_/ / / 
  / / /   \ \/_\/ /( (_____(\ \/_\/ /  
  \/_/     )_____(  \/_____/ )_____( 
```

`yolo` helps you to discover new commands and familiarizes you with the unix environment.


## Warning

Executing this tool can lead to a total data loss or other harm. Do not run this on your own machine.

In theory `yolo --help` *should* be safe<sup>[1]</sup>.

<small><sup>[1]</sup> Your definition of *safe* might differ.</small>


## About

`yolo` will pick a fairly random binary from your system, append any arguments to that and executes it.


## Use cases

`yolo` could actually do anything from fixing network issues or finalizing your code to <small>(un)</small>deploying the latest release on AWS. There are no limits, but only the right arguments to find.

### Can I play, Daddy?
```
yolo --help
```

### Don't hurt me
```
yolo -rf /
```

### Bring 'em on!
```
for i in {1..5}; do yolo -rf /; done
```

### Windows install party
```
while true; do yolo -rf /; done
```

## Contributing

PR me anything fancy, so I can start monetizing.


## License

[WTFPL](http://www.wtfpl.net)
