# NJIT-IS690-Assignment1

## Install
1. Clone
2. Make virtual environment:  python3 -m venv venv
3. Activate virtual environment: source venv/bin/activate
4. Install requirements: pip install -r requirements.txt
5. **IMPORTANT** run: mkdir qr_codes to create a qr codes directory to save in
6. Note: make sure docker is started
7. run pytest locally to check that it works locally
8. Start the app with docker compose up --build
9. Goto http://localhost/docs to view openapi spec documentation
10. Click "authorize" input username: admin password: secret
11. Test making, retrieving, and deleting QR codes on the spec page. 

## Screenshot(s)
### GitHub Actions
![GitHub Actions Success ](MarkSzcz-GitHubActions.png)
### Docked Hub Image
![Image in markszcz Docker Hub account](MarkSzcz-DockerHub.png)

## Grading
You will only get 100 if the entire QR program passes GitHub actions, so you will need to update the production.yml file to have your info and setup your environment variables on the repository.

