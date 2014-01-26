
cd /your/path/to/superposition
cd ../hackneygrove

bash script that does the following

superposition init

mkdir components static nginx test config
cp ../superposition/*.sh .
cp ../superposition/.editorconfig .
cp ../superposition/.gitignore .
cp ../superposition/nginx/*.template nginx
cp ../superposition/nginx/*.yaml nginx
cp ../superposition/nginx/generate.js nginx
cp ../superposition/nginx/setup.sh nginx
cp ../superposition/static/index.html static


superposition
