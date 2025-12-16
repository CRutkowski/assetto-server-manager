deps:
	npm install --legacy-peer-deps --ignore-scripts
	npm rebuild

build: deps
	./node_modules/.bin/gulp build

watch: deps
	./node_modules/.bin/gulp
