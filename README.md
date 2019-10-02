# Linux-Challenges
# Task 1.
ls
pwd
mkdir workspace
cd workspace
ls
touch ReadMe.md
cp ReadMe.md ChangeLog.md

# Task  2.
touch exercise.md
mv exercise.md /tmp
rm exercise.md


# Task  3.
touch umuzi.md recruits.md cohort.md
nano umuzi.md
Delayed by time to be right on it - Kwena Peu
ctrl+x

nano recruits.md
Insanity keeps me company when my thoughts take afternoon walks. - Hlox De Rebel
ctrl+x


nano cohort.md
Remember To Forget How To Not Remember. - Kwena Peu 
ctrl+x


cat cohort.md recruits.md umuzi.md > summary.md
echo The End >> summary.md

# Task  4.
locate umuzi.md
locate umuzi.md >> search_result.md

# Task  5.
cd Documents/
touch pad.md
cd
cd Desktop/
cp ~/Documents/pad.md . 
mv pad.md pad_copy.md
locate updatedb
cd
locate pad_copy.md


# Task 6.

find ~/ -name *.pdf

find ~/ -name *.pdf >> results_search.txt

find ~/ -atime 1


# Task 7.

nano my_bio.md
ctrl+s
