# Change Log

All notable changes to the ".ssai" extension will be documented in this file.

Check [SoluaScript](http://keepachangelog.com/) for recommendations on how to structure this file.

## Version [1.0.0] - 2023-06-06

- SoluaScript (.ssai) - An AI-focused scripting language

Added ACTIVATE_AI() ENTER command. Enter the complete path to the AI executable within the parentheses, using double quotes around the entire path ACTIVATE_AI("...\chatGPT.exe"), then press ENTER to activate the AI.

Added TRAIN_AI() ENTER command. Enter the complete path to the training book with the .txt extension within the parentheses, using double quotes around the entire path TRAIN_AI("...\Learn Python.txt"), then press ENTER to start the AI training.

Added writeIn() ENTER command. Enter the name and extension of the other language you want to write within the parentheses, using double quotes around the name writeIn("JavaScript"), then press ENTER. GraalVM-CE-22.3.2 will provide a prompt with the JavaScript language for coding.

Added automatic PRINT process, but it is not fully implemented yet. It will serve as the real-time training monitor for the AI, triggered once the AI training starts.

Added automatic ANOTHER_LOGIC process, which is currently not implemented and unused.