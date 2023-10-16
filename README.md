# bq-python-client-adc-keyless

This project shows how to launch a Python script using a Google Cloud Python client, without a SA token key and enabling 
keyless approach with Application Default Credentials.

The example is shown from IntelliJ Idea.

With this technic, developers can launch their GCP applications without a SA token key that is a more secure approach\
because it prevents to download a long-lived token key.

![bq_python_client_with_adc.png](diagram%2Fbq_python_client_with_adc.png)