<div align="center">

<h1>randheimer</h1>

Kernel drivers, hypervisors, reverse engineering.

[![Profile Views](https://komarev.com/ghpvc/?username=randheimer&color=blueviolet&style=for-the-badge)](https://github.com/randheimer)
[![GitHub followers](https://img.shields.io/github/followers/randheimer?style=for-the-badge&color=blue)](https://github.com/randheimer?tab=followers)
[![GitHub Stars](https://img.shields.io/github/stars/randheimer?style=for-the-badge&color=yellow)](https://github.com/randheimer?tab=repositories)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/randheimer/randheimer/output/github-contribution-grid-snake-dark.svg" />
  <img alt="Contribution graph snake" src="https://raw.githubusercontent.com/randheimer/randheimer/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## About

<details>
<summary>about.go</summary>

```go
package main

import "fmt"

type Stack struct {
	Kernel    []string
	Offensive []string
	Reverse   []string
	Tools     []string
}

type Engineer struct {
	Name      string
	Role      string
	Stack     Stack
	Languages []string
}

func (e *Engineer) Introduce() string {
	return fmt.Sprintf("%s, %s", e.Name, e.Role)
}

func main() {
	dev := &Engineer{
		Name: "randheimer",
		Role: "Systems Engineer",
		Stack: Stack{
			Kernel:    []string{"Windows Drivers", "Hypervisors", "Custom OS"},
			Offensive: []string{"Lua Obfuscation", "Enterprise Obfuscation", "Memory Encryption"},
			Reverse:   []string{"Binary Analysis", "Hooking", "Anti-Debug Bypass"},
			Tools:     []string{"KaizerIDE", "PDF-Fusion", "Game Tools", "System Utilities"},
		},
		Languages: []string{"C++", "Rust", "Go", "C", "Assembly", "Lua", "Python", "JavaScript"},
	}

	fmt.Println(dev.Introduce())
}
```

</details>

---

## Tech stack

| Area | What I use |
|---|---|
| Languages | C++, Rust, C, Go, Assembly, Lua, Python, JavaScript |
| Kernel and systems | Windows kernel drivers, hypervisors, custom OS |
| Reverse engineering | Binary analysis, hooking, anti-debug bypass |
| Obfuscation | Lua obfuscation, enterprise obfuscation, memory encryption |
| Tools and platforms | Git, GitHub, VS Code, Windows, Linux, Electron |

---

## Featured projects

- [PDF-Fusion](https://github.com/randheimer/PDF-Fusion), Python. Offline desktop app for merging PDF and image files. Drag files in, reorder them, preview, and save one PDF.
- [roblox-multi-instance](https://github.com/randheimer/roblox-multi-instance), Python.

---

## GitHub stats

<div align="center">
  <img width="32%" src="https://github-readme-stats.vercel.app/api?username=randheimer&show_icons=true&theme=radical&count_private=true&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
  <img width="32%" src="https://streak-stats.demolab.com?user=randheimer&theme=radical&hide_border=true&background=0D1117" alt="GitHub Streak" />
  <img width="32%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=randheimer&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&langs_count=8" alt="Top Languages" />
</div>

---

<div align="center">

### 💭 *"We are Anonymous. We are Legion. We do not forgive. We do not forget. Expect us."*

*Anonymous*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="" width="100%"/>

</div>
