# Deno-PLC [WIP]

This is a collection of libraries, templates and code snippets to build [PLC](https://en.wikipedia.org/wiki/Programmable_logic_controller) and PLC-related applications with [Deno](https://deno.com/) and TypeScript.

With the help of the projects within this organization you can build HTML5 HMI Panels, Home automation applications and everything else which introduces communication with hardware IO devices.

## Sub-projects:

* [`sACN-Deno`](https://github.com/LMGU-Technik/sACN-Deno) Deno port of [k-yle/sACN](https://github.com/k-yle/sACN)
* [`rollup-plugin-jsr`](https://github.com/deno-plc/rollup-plugin-jsr/) Native JSR loader for Rollup/Vite (WIP)

## Safety Notice

Do ***NEVER*** use any part of this project in ***SAFETY CRITICAL*** systems. 
Software written in languages like JS/TS is not suitable for such applications, because code execution is highly undeterministic (especialy the V8 JIT) and does not meet any hard timing requirements.
Safety critical systems require [special](https://en.wikipedia.org/wiki/Programmable_logic_controller#Safety_PLCs) certified Hard- and Software
