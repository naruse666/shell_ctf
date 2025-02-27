# shell_ctf

1. First, go to the directory for the problem you want to solve. 
```sh
cd beginer/1
```

2. You can generate an answer template with the `make init` command.
```sh
make init
```

After execution, a directory like this will be created.
```sh
tree
.
├── Makefile
├── README.md
├── naruse_murai        # generated
│   ├── answer.sh       # generated
│   └── referer_rfc.txt # generated
└── referer_rfc.txt
```

3. Please read `README.md` and answer the questions in `answer.sh`.
4. You can send answer with `make answer` command.
```sh
make answer
```

5. Open the PR and check the solution.
e.g. https://github.com/naruse666/shell_ctf/pull/1
