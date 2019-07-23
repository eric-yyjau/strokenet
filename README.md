# StrokeNet  
Check out this work, neural renderer + RL works better
https://github.com/hzwer/SARA_DDPG

## Requirements
- npm
  - mac
  ```
  brew install node
  ```
  - ubuntu
  ```
  
  ```

## Run training
 ```
 mkdir model
 ```
- Train coord_encoder

- Train generator
  - Generate data
  ```
  cd environment
  npm install
  npm audit fix
  ```


## Results
A neural network that learns to draw digits by strokes  
The environment relies on node.js and puppeteer  
Needs tweaking to get it work  
MNIST (left MNIST sample, middle generator output, right Draw Web App reconstruction)  
![avatar](https://github.com/vexilligera/strokenet/blob/master/figures/mnist_result.png?raw=true)  
Omniglot  
![avatar](https://github.com/vexilligera/strokenet/blob/master/figures/omniglot_result.png?raw=true)  
