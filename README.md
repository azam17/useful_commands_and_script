# useful_commands_and_script
list of one liners and script that i can refer back if needed

1: To add dummy fasta header and ensure a newline after the addition of fasta header

    for file in *.fa; do sed -i '1s/^/>1 \n/' "$file"; done

2: python scripts to extract sequences based on contigs header/fasta header (without the ">") and the coordinates (sequences bp and end), this is useful when i wanted to visualize genes using clinker. script link: [TBA]

      
