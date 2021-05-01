.PHONY: build
build:
	docker-compose build

.PHONY: setup
setup:
	docker-compose run --rm app npm install

.PHONY: bash
bash:
	docker-compose run --rm app bash

.PHONY: test
test:
	docker-compose run --rm app npm run test
