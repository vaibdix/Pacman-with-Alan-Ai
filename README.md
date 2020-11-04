# Pacman-with-Alan-Ai
    just a pacman game wih voice functions using Alan AI.

### Implementation of Alan AI
 
    - Go to https://studio.alan.app/
    - Signup 
    - Click Create Voice Assistant
    - add the following in editior
        ## 
        ```
        intent('Hello world', p => {
            p.play('Hi there');
        });

        intent('left', p => {
            p.play({command: 'go-left'})
        });
        
        intent('right' , p => {
            p.play({command: 'go-right'})
        });
        
        intent('up' , p => {
            p.play({command: 'go-up'})
        });
        
        intent('down' , p => {
            p.play({command: 'go-down'})
        });
        
        intent('start game', p =>{
            p.play({command: 'start-game'})
        });        
        ```
    - copy Alan SDK Key and replace it in code and it done.

### MIT Licence

Copyright (c) 2020 Vaibhav Dixit

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

*Translation: Ofcourse you can use this for you project! Just make sure to say where you got this from :)

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
