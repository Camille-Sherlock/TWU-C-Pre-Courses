**linux练习**

mkdir cli-practice

cd cli-practice

touch readme.md

echo “Hi there, this is a readme file.”>> ./readme.md

echo“This is the second line of the readme file.”>> ./readme.md

mv readme.md readme.txt

mkdir document

mv readme.txt ./document

mv ./document/readme.txt ./document/introduction.txt

cd document

cp introduction.txt readme.txt

echo “The quick brown fox jumps over a lazy dog ”>./readme.txt

cd ..

cp -ri ~/cli-practice/document ~/cli-practice/docs

rm -rf ~/cli-practice/document 

mkdir -p ~/cli-practice/parent/child/docs  

cp ~/cli-practice/docs/introduction.txt ~/cli-practice/parent/child/docs