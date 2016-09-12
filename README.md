# reshell

Augmented shell with reason toolchain for developers who install reason through npm 

## Setup

```
git clone https://github.com/facebook/reason # skip this if you already have reason cloned
git clone https://github.com/reasonml/reshell
cd reshell
npm link ../reason # link local reason 
npm install # install dependencies
npm link # link commands globally
```

## Usage
In any directory, type
```
rebash # to get a bash session
```
or 
```
rezsh # to get a zsh session
```
or 
```
refish # to get a fish session
```
You will get a virtual env shell with reason commands.


