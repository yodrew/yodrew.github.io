egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd _includes
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../_posts
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../_pages
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd front
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../back
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../report
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../store
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../other
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../conjecture
egrep -o "\[[^]]+\]\([^/][^)]+" *.md | cat > link.md
cd ../../
cat link _include/link.md _posts/link.md 
