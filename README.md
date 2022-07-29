# RequestKeyVaultAzure
This script did for extract the Key Vault the Azure. You can do the security test.

Welcome to the RequestKeyVaultAzure wiki!

When this script python you can extract the secret in Key Vault service of Azure, where you can appky the nexts steps.

Requirement: Python3 Linux Ubuntu, Debian, Kali linux.

git clone https://github.com/henochjelvez/RequestKeyVaultAzure.git


1) You shoud install the libraries 
• pip3 install azure-common 
• pip3 install azure-cli-profile 
• pip3 install azure-mgmt-resource 
• pip3 install azure.identify 
• pip3 install azure-keyvault-secrets

2) You can edit the file add the next variables.

4) KeyvaultName = "Yo KeyVault name" 
KVVUri = f"https://KeyVaultName.vault.azure.net" 
SecretName = "Yo secret name"

For execute the profile 
#python3 requestKeyVaul.py

You can see the secret
