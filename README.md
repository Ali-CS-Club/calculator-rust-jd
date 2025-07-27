# Calculator Project – Rust

![Ferris the Crab](https://www.rust-lang.org/static/images/ferris.gif)

👤 JD

---

This is my personal Rust calculator project.  
It includes both:

- `cli/` – A terminal-based calculator written in idiomatic Rust.  
- `gui/` – A graphical calculator using a modern Rust GUI framework like `egui` or `iced`.

Each version is in its own folder and built using `cargo`.

---

## 📁 Project Structure

```
calculator-rust-jd/
├── cli/
│   └── calculator.rs         # CLI version – compiled & run with Cargo
└── gui/
    └── calculator_gui.rs     # GUI version – built with egui or iced
```

---

## 🚀 How to Run

### CLI Version

```bash
cd cli
cargo run
```

### GUI Version

> ⚠️ Requires dependencies such as `egui` or `iced` to be added to your `Cargo.toml`

```bash
cd gui
cargo run
```

---

## 📚 About This Project

The CLI version focuses on implementing arithmetic logic using core Rust features such as:

- Pattern matching  
- Enums  
- Ownership and error handling

The GUI version introduces user interfaces and visual design using event-driven architecture and state management.  
Crates like `egui` or `iced` are used to build interactive layouts with idiomatic Rust.

---

```
  (v)^__^(v)
    Ferris!
```

---
