# @Deno-PLC

This is a collection of libraries, templates and code snippets to build [PLC](https://en.wikipedia.org/wiki/Programmable_logic_controller) and PLC-related applications with [Deno](https://deno.com/) and TypeScript.

With the help of the projects within this organization you can build HTML5 HMI Panels, Home automation applications and everything else which introduces communication with hardware IO devices.

> [!WARNING]
> Do ***NEVER*** use any part of this project in ***SAFETY CRITICAL*** systems. 
> Software written in languages like JS/TS is not suitable for such applications, because code execution is highly undeterministic (especialy the V8 JIT) and therefore does not meet any hard timing requirements.
> Safety critical systems require [special](https://en.wikipedia.org/wiki/Programmable_logic_controller#Safety_PLCs) certified Hard- and Software
> 
> Nevertheless you can use TypeScript to communicate with such Safety-PLCs

## Projects:

* [`vite-plugin-deno`](https://jsr.io/@deno-plc/vite-plugin-deno) Use Deno imports (jsr:, https://, ...) with Vite and drop `node_modules`.
* [`signal-utils`](https://jsr.io/@deno-plc/signal-utils) Small and easy to use utilities for Preact Signals that simplify usage in async code, with Sets, Maps and as timers
* [`sACN-Deno`](https://github.com/LMGU-Technik/sACN-Deno) Deno port of [k-yle/sACN](https://github.com/k-yle/sACN)
* [`slip`](https://jsr.io/@deno-plc/slip) TypeScript implmentation of SLIP (Serial Line Internet Protocol)
* [`adapter-tcp`](https://jsr.io/@deno-plc/adapter-tcp) TCP device adapter
* [`adapter-osc`](https://jsr.io/@deno-plc/adapter-osc) Device adapter for OSC (Open Sound Control)
* more device adapters coming soon...

