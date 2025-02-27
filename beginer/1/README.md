[referer_rfc.txt](./referer_rfc.txt)は、HTTPヘッダのRefererに関するRFCを抜粋したものです。  
original refs: https://datatracker.ietf.org/doc/html/rfc7231#section-5.5.2  

しかし、`Referrer`を`Referer`とスペルミスをしてしまいました...  

`Referrer`を`Referer`に置換するコマンドを`your_name-answer.sh`に記述してください。

# 問題を解く
1. You can generate an answer template with the `make init` command.
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

2. Please read `README.md` and answer the questions in `answer.sh`.
3. You can send answer with `make answer` command.
```sh
make answer
```

4. Open the PR and check the solution.
e.g. https://github.com/naruse666/shell_ctf/pull/1

