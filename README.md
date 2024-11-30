# AI-Books
Cheat for Become AI Developer

docker run --restart=always -d --add-host=host.docker.internal:host-gateway -v "/home/macbookairm2/ollama:/root/.ollama" -p 11434:11434 --name ollama --hostname my-ollama ollama/ollama

docker exec -it ollama ollama run qwen2.5-coder:14b
