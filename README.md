# SoluaScript README

SoluaScript (.ssai)
SoluaScript is a simple scripting language aimed at training AIs on personal computers. It functions as a domain-specific language (DSL) focused solely on training AIs through reading books in text format.

## Features

1 - Trains AI through book reading.

## Requirements

Currently, we are observing how the language behaves in this initial version as we are not sure how GraalVM-CE-22.3.2 will interact or interfere with the overall process. If it requires installation on users' machines, we hope that SoluaScript (.ssai) will continue to function independently of the ability to execute JavaScript.js through GraalVM, as JavaScript.js is just an additional implementation in our language.

## Extension Settings

This extension does not contribute any additional settings to Visual Studio Code.

## Known Issues

We are investigating...

## Release Notes

In this initial version, the language has a limited set of commands, which facilitates integration with other languages.

### 0.0.1
In this first version, the available commands are:

ATIVAR_IA("path_to_IA_executable.exe") ENTER
TREINAR_IA("path_to_book.txt") ENTER
IMPRIMIR
OUTRA_LOGICA("Some logic")

Within the IDE, you can enter the commands as follows:

ATIVAR_IA("path_to_IA_executable/ChatGPT3.5.exe") ENTER
TREINAR_IA("path_to_book_extension/Learn_Python_from_Zero_to_Advanced.txt") ENTER

Pressing ENTER after each command will trigger the corresponding action. When activating the AI, it will wait for the next command. The TREINAR_IA command will initiate the AI training, where it will read and learn from the specified book. During training, the IMPRIMIR command will display the real-time completion percentage of the training. We have not fully implemented the logic for the IMPRIMIR command yet, but we plan to show the training progress.

The SoluaScript language aims to provide lightweight, fast, and resource-efficient AIs in terms of processor, memory, and disk space. We are in the final stages of language development and plan to publish the project on GitHub soon. We welcome contributions from anyone interested.

By using the command escreverEm("JavaScript"), GraalVM will recognize and automatically enable the ability to write in that language. To switch back to writing in SoluaScript, simply use the command escreverEm("off").

We are excited about the development of the SoluaScript language and hope that it can be a useful tool for training personal AIs in a simple and efficient manner when it becomes fully functional.

### 0.0.2

