# beelib
Bee Lib: a Bash Project Library

## 1.a. use into exising git project
`git submodule add https://github.com/lonesoft/beelib`

## 1.b. use into empty project
`git clone https://github.com/lonesoft/beelib`  

## 2. initialize git (optional)
```
git init  
git submodule add ./beelib  
```

## 3. install beelib
`beelib/project-install [project name]`

## 4. commit git (optional) 
```
echo /local >> .gitignore
echo "## install" >> README.md
echo "git clone --recurse-submodules https://github.com/foo/bar" >> README.md
git add .
git commit -m "install beelib"
```

## 5. start project
`./project`

## 6. clone project with beelib submodule
`git clone --recurse-submodules https://github.com/foo/bar`
