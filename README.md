git clone https://github.com/FillhartK/collab-assignment
cd collab-assignment
echo "Collaborator made this change." >> project.txt
git add project.txt
git commit -m "Collaborator updated the project file"
git push origin main
