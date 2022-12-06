echo "Hello, World" -> prints the "Hello, world"

echo "\"(Ôo)'" -> prints confused smiley face

cat /etc/passwd -> display contents of the file

cat /etc/passwd /etc/hosts -> display contents of 2 files

tail -n 10 /etc/hosts -> display last 10 lines

head -n 10 /etc/passwd -> display first 10 lines

head -n 3 iacta | tail -n 1 -> displays 3rd line only from the file

echo "Best School" -> create file with exact name

ls -la > ls_cwd_content -> write into ls_cwd the results of ls -la

tail -n 1 _filename_ >> _filename_ -> duplicate last last of a file (>> means must not overwrite if it exist

find . -type f -name "*.js" -delete -> delete files with .js extension

find . -mindepth 1 -type d |wc -l -> coubt no. of dir excluding current one

find . -type f -printf "\n%AD %AT %p" | head -n 10 -> display 10 newest files and sort by date
or use this command ls -t1 | head -n 10

sort | uniq -u -> print words that appear exactly once and must be sorted

grep -i _"root"_ /tec/passwd -> display lines with the pattern "root"

grep -c "bin" /etc/passwd -> count no. of line with word "bin"

grep -i "root" -A 3 /etc/passwd -> display lines containing "root" and 3 lines after it

grep -v "bin" /etc/bin/ -> display lines not containing "bin"

