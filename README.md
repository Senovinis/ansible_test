# ansible_test
Ansible testing repository AUJ
Added line for test
Pilni mokymai

which git
#jei nieko nemeta reik irasyt
sudo apt update
git
#cia turi but ssh kejus, kurio public keju reik ikelti git
cat .ssh/id_ed25519.pub
#gite webe Code->clone ssh ir kopijuojam i zemiau (viska kopijuot)
git clone git@github.com:usris/repositorija.git
ls
cd repositorija/
cat README.md

# zemiau mano atveju Senovinis, o ne vardas pavarde, o mailas pagrindinis
git config --global user.name "Vardas Pavarde"
git config --global user.email "mailas@mailas.com"
#rezultata galima rast cat ~/.gitconfig

nano README.md
#modifikuoju
git status
git diff README.md

git add README.md
git commit -m "cia rasau zinute kas keista"
git push origin main
Pilni mokymai komanda ne git push origin master, o git push origin main
