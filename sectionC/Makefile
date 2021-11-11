install: venv
	.venv/bin/activate; pip3 install -r requirements.txt

venv:
	test -d venv || python3 -m venv venv

clean:
	rm -rf venv
	find -iname "*.pyc" -delete
run:
	python kMeans_Plot.py
