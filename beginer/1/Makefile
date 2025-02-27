user = $$(whoami)
num := "1"
BRANCH_NAME = $(shell git branch --show-current)

init:
	@mkdir -p $(user)
	@cd $(user) && touch answer.sh && chmod 700 answer.sh && cp ../referer_rfc.txt .

answer:
	if [ $(BRANCH_NAME) == "main" ]; then git checkout -b $(user)-$(num) && $$(git add $(user)/* && git commit -m "$(user): answer $(num)" && git push origin $(user)-$(num)); else $$(git add $(user)/* && git commit -m "$(user): answer $(num)" && git push origin $(user)-$(num)); fi
