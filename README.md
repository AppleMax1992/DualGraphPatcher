Code for Leveraging Syntactic Dual-Graph Representations for Security Patch Identification via Structual Latent Alignment

To build the abstract syntax tree (AST) for the diff codes, we are using an older version of tree_sitter==0.21.3. Therefore, you will need to manually download the corresponding tree-sitter-parser for each language and set the correct version for each parser. For example: 1. `git clone https://github.com/tree-sitter/tree-sitter-cpp` 2. `git reset --hard bbaecd50bad60a062fef5829fcbc4dc2ac7991fd`

You can use pip install -r requirements.txt to achieve minimal environment reproduction.
