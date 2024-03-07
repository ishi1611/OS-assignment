mkdir LinuxAssignment
cd LinuxAssignment
touch file1.txt
ls
vi file1.txt
cat file1.txt
mkdir docs
cd docs
mv file1.txt file2.txt
ls
cat file2.txt
chmod 744 file2.txt
sudo mv file2.txt ../file2.txt
ls * | grep \.txt$
grep "i" file2.txt
date
time
sudo apt install net-tools
ifconfig
ping
ls -l
head -10 data.txt
tail -5 data.txt
tr [:lower:] [:upper:] <input.txt> output.txt
sort duplicate.txt | uniq

  216  tail -6 data.txt
