# Deploy de Aplicação Utilizando Container no Cloud Run

1) Clone de repositório:

$ git clone https://github.com/GoogleCloudPlatform/python-docs-samples


2) Acessando diretório:

$ cd /python-docs-samples/run/helloworld


3) Container Registry

$ export GOOGLE_CLOUD_PROJECT=VALOR

$ gcloud builds submit --tag gcr.io/${GOOGLE_CLOUD_PROJEC}/helloworld

4) Deploy através do Cloud Run


