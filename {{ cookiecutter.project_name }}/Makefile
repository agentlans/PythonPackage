.PHONY: install uninstall clean

install:
	pip3 install . -r requirements.txt

uninstall:
	pip3 uninstall {{ cookiecutter.project_name }}

clean:
	rm -r build {{ cookiecutter.project_name }} {{ cookiecutter.project_name }}.egg-info
