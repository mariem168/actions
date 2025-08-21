
This project configures a self-hosted GitHub Actions runner that prints an ASCII dragon using `cowsay`.

## How to Start/Stop the Runner

From the `actions-runner` directory:

```bash
# Start the runner
./run.sh

# Stop the runner
CTRL + C
 
# how to rerun the job
## make a new comit and push to the main 
git add .
git commit -m "Trigger dragon CI"
git push origin main

