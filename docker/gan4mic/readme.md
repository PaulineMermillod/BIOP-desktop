docker run -it --rm -p 8888:8888 --gpus device=0  --mount src=F:/00000-pauline/,target=/home/biop/local,type=bind 

#cd docker + change name if create a new version 
docker build -f gan4mic\Dockerfile-gan4mic  -t biop-gan4mic:0.0.1 . 