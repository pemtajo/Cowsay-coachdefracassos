## :dragon: Bushido dragon

```
/ No masterpiece was ever created by a \
\ lazy artist.                         /
 --------------------------------------
      \                    / \  //\
       \    |\___/|      /   \//  \\
            /0  0  \__  /    //  | \ \    
           /     /  \/_/    //   |  \  \  
           @_^_@'/   \/_   //    |   \   \ 
           //_^_/     \/_ //     |    \    \
        ( //) |        \///      |     \     \
      ( / /) _|_ /   )  //       |      \     _\
    ( // /) '/,_ _ _/  ( ; -.    |    _ _\.-~        .-~~~^-.
  (( / / )) ,-{        _      `-.|.-~-.           .~         `.
 (( // / ))  '/\      /                 ~-. _ .-~      .-~^-.  \
 (( /// ))      `.   {            }                   /      \  \
  (( / ))     .----~-.\        \-'                 .~         \  `. \^-.
             ///.----..>        \             _ -~             `.  ^-`  ^-_
               ///-._ _ _ _ _ _ _}^ - - - - ~                     ~-- ,.-~
                                                                  /.-~

```
Inspiring quotes in your terminal.

## Requirements

* Jq
```
sudo apt install jq 
```

* Curl
```
sudo apt install curl
```

* Cowsay
```
sudo apt install cowsay
```

## Install



If you use **bash**, paste the script below in the **.bashrc**. Or, if your use **zsh**, paste in the file **.zshrc**
 
```
curl -s  https://raw.githubusercontent.com/pemtajo/bushido-dragon/master/quotes.json | jq -r '.[] | .quote ' | sort -R | head -n 1 | cowsay -f dragon
```
