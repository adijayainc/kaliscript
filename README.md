# ollama-modelfiles for adijayainc
Model gen AI dengan system yang dimodifikasi sesuai keperluan , kemudian disimpan di ollama portal

https://ollama.com/adijayainc/

mekanisme upload menggunakan perintah sebagai berikut : 
'
ollama pull llama3.2
echo "FROM llama3.2" >> Modelfile
echo "SYSTEM You are a friendly assistant." >> Modelfile
ollama create -f Modelfile adijayainc/bhsa-qwen2.5-1.5b
ollama push adijayainc/bhsa-qwen2.5-1.5b
