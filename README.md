# useful_commands_and_script
list of one liners and script that i can refer back if needed

1: To add dummy fasta header and ensure a newline after the addition of fasta header
for file in *.fa; do sed -i '1s/^/>1 \n/' "$file"; done
