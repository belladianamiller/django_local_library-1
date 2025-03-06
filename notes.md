1. Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate
2. Install Python dependencies
pip install -r requirements.txt
3. Run migrations
python3 manage.py makemigrations
python3 manage.py migrate
4. Start the server
python3 manage.py runserver
5. Login to admin site
python3 manage.py createsuperuser
6. Mutate the state
add a book, author, book instance, etc.
7. Commit changes
fork repository
8. Add a remote repo
git remote add github [SSH_URL]
9. Push commits to the github remote
git push github main --force
10. Create tag
git tag -a v1.0 -m "Submission"
git push github v1.0