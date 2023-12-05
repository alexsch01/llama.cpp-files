# Build Instructions
```
git clone https://github.com/alexsch01/llama.cpp-upstream -b custom test
cd test
make
```

# After editing file in `examples/server/public` folder
(example `index.html`)
```
xxd -i index.html > ../index.html.hpp
```
