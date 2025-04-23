all: test

test: venv
	./venv/bin/pytest

venv:
	python3 -m venv venv
	venv/bin/pip install -r requirements.txt

clean:
	rm -rf venv
