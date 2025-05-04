---
title: "Mastering Vim & Neovim"
subtitle: "From Basic Commands to Advanced Workflows"
---

# Agenda
1. Vim Basics
2. Why Vim?
3. Configuration & Plugins
4. Macros & Advanced Editing
5. IDE & Browser Integration
6. Advanced Demos
7. Brain-Friendly Delivery
8. Fuel Up & Cinnamon Buns
9. Summary & Q&A

---

# Vim Basics
## Modes & Navigation
- Normal, Insert, Visual, Command-line modes
- `h`, `j`, `k`, `l` to move left/down/up/right
- `i` to insert, `x` to delete, `p` to paste
- `:w` to save, `:q` to quit, `:wq` to save & quit

---

# Why Vim?
- **Ergonomics:** Mouse-free editing reduces strain
- **Speed:** Powerful shortcuts for rapid text manipulation
- **Customization:** Tailor your editor to any workflow
- **Challenge & Fun:** The puzzle of modal editing

---

# Configuration & Plugins

## .vimrc Essentials
```vim
set number          " Show line numbers
syntax on           " Enable syntax highlighting
set tabstop=4       " Tab = 4 spaces
set shiftwidth=4    " Auto-indent = 4 spaces
set expandtab       " Use spaces instead of tabs
```

## Plugin Managers
- **vim-plug**
- **Vundle**
- **Pathogen**

---

# Macros & Advanced Editing
- **Macros:** Record (`q` + register) → replay (`@`)
- **Text Objects:** `ci"` (change inside quotes), `da(` (delete around parens)
- **Global Commands:** `:g/pattern/s//replacement/g` for project-wide edits

---

# IDE & Browser Integration

## IDE Plugins
- **IdeaVim** in JetBrains IDEs
- **VSCodeVim** extension for VS Code

## Browser Plugin
- **Vimium** for keyboard-driven web navigation

---

# Advanced Demos

## 1. Performance Tuning
- Profile startup: `nvim --startuptime` → identify slow plugins
- **Lazy-load** critical plugins on demand
- Disable unused providers (e.g., Ruby/Python)

## 2. Plugin Architecture Deep Dive
- **Vimscript** vs **Neovim’s Lua + RPC**
- Asynchronous plugins via RPC API
- Example: Write a 3-line Lua plugin and map a key

## 3. Remote Pairing
- Terminal sharing with **tmux + tmate**
- Demo: Live collaborative edit, two cursors, shared splits

## 4. Neovim IDE Features
- **Built-in LSP**: go-to-definition, autocompletion, hover docs
- **Tree-sitter**: semantic highlighting & advanced text objects

---

# Brain-Friendly Delivery
- **Chunking:** Break content into 5–7 minute segments with mini-recaps
- **Spaced Repetition:** Revisit 3 core takeaways in new contexts
- **Dual Coding:** Combine live demos with simple diagrams/slides
- **Cognitive Load:** Scaffold complexity, narrate each keystroke, pause & clarify

---

# Fuel Up & Cinnamon Buns 🍩
- **Boost morale:** Sweet incentive between demos
- **Enhance focus:** Glucose kick for sustained attention
- **Celebrate:** Coding + cinnamon buns = unbeatable combo

---

# Summary & Next Steps
- **Performance Hacks**: Lazy-load & profiling
- **Plugin Power**: Lua, async, RPC architecture
- **Collaboration**: tmux/tmate pairing
- **Advanced Workflows**: LSP, Tree-sitter, macros
- **Brain-Based Tips**: Chunk, repeat, visualize, scaffold

Feel free to explore more and tweak your own setup!

---

# Q&A
Any questions or feedback? Let’s make Vim even sweeter!
