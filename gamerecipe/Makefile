install:
	pip install -r requirements.txt

dev-install:
	pip install -r test-requirements.txt

wipe_db:
	rm -rf db.sqlite3

serve:
	python manage.py runserver

clean:
	find . -type f -name '*.pyc' -delete

make_migrations:
	python manage.py makemigrations

merge_migrations:
	python manage.py makemigrations --merge

migrate:
	python manage.py migrate

shell:
	python manage.py shell
