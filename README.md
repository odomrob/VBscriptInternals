# VBscriptInternals
Scripts for disassembling VBScript p-code in the memory to aid in exploits analysis

Author: [Boris Larin](https://twitter.com/oct0xor)

This repository contains
scripts for disassembling VBScript p-code in the memory to aid in exploits
analysis.

## Contents

`kl_vbs_disasm_ida.py` -
Script for IDA Pro 

`kl_vbs_disasm_windbg.py`
- Script for WinDbg with PyKD extension

## Usage

Set breakpoint at
function `vbscript!CScriptRuntime::RunNoEH` and use appropriate script after breakpoint is hit. 
