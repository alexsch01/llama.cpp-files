### Build Instructions
```
git clone https://github.com/alexsch01/llama.cpp-files test
cd test
make
```

### After editing file in `examples/server/public` folder
(example `index.html`)
```
xxd -i index.html > ../index.html.hpp
```
