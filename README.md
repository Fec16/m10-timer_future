# Tutorial-8

### Refleksi

![Image 1](assets/images/img1.jpg)

Based on the observation, the async function will execute outside the main function that calls it. Hence, *"hey hey"* might be outputted before *"howdy!"* and *"done!"* since *"hey hey"* is outside the async function. 

The program continues and executes `println!("hey hey")`; while the async function is still waiting for future's result.