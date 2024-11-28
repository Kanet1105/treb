# Treb

## Prerequisites
```
sudo apt-get install build-essential pkg-config libxcb-render0-dev libxcb-shape0-dev libxcb-xfixes0-dev libxkbcommon-dev libssl-dev
```

```
cargo install --locked trunk
```

## Guides
1. Clone the repository:
```
git clone https://github.com/kanet1105/treb
```

2. Move into the directory:
```
cd treb/crates/treb-gui
```

3. Install wasm32
```
rustup target add wasm32-unknown-unknown
```

4. Play with it and test it locally using `trunk`:
```
trunk serve
```
