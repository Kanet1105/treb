# Treb

## Prerequisites
```
sudo apt-get install build-essential pkg-config libxcb-render0-dev libxcb-shape0-dev libxcb-xfixes0-dev libxkbcommon-dev libssl-dev
```

```
rustup target add wasm32-unknown-unknown
```

```
cargo install --locked trunk
```

# Guides
1. Clone the repository:
```
git clone https://github.com/kanet1105/treb
```

2. Move into the directory:
```
cd crates/treb-gui
```

3. Play with it and test it locally using `trunk`:
```
trunk serve
```