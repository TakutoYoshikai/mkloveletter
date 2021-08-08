# mkloveletter
mkloveletter is generator of capsule of loveletter. It generates executable file to output the love letter. but, it outputs secret data after given time.

### Requirements
* Linux
* Rust
* Cargo

### Usage
**install**
```bash
git clone https://github.com/TakutoYoshikai/mkloveletter.git
cd mkloveletter
./install.sh
# if you want to register the bin directory to $PATH
echo "export PATH=\$PATH:/path/to/mkloveletter/bin" >> ~/.bashrc
```

**make love letter**
```bash
mkloveletter /path/to/secret-file /path/to/love-letter "2021-01-02-12-13-00-+0900"
```

**show love letter**
```bash
./file.loveletter
```

### LICENSE
MIT License
