#!/bin/bash
echo 'Hello, World'                     prints “Hello, World”, followed by a new line
echo "\"(Ôo)'"                          displays a confused smiley "(Ôo)'
cat /etc/passwd                         displays the content of /etc/passwd
cat /etc/passwd /etc/hosts              Display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd                  Display the last 10 lines of /etc/passwd
head -n 10 /etc/passwd                  Display the first 10 lines of /etc/passwd
head -n 3 iacta | tail -n 1             displays the third line of the file iacta
echo Best School >\\\\\\\"'\"Best School\"\\'"\\\\\\$\\\?\\\\\\\\\\\\\\\*\:\)         creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School
ls -la > ls_cwd_content                 writes into the file ls_cwd_content the result of the command ls -la
