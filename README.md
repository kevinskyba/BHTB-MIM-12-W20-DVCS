# BHTB-MIM-12-W20-DVCS

Schritte:


---


`git clone https://github.com/kevinskyba/BHTB-MIM-12-W20-DVCS.git`
`git add .`
`git commit -m "Added new steps"`
`git push`


---


`git diff HEAD^^ README.md`:
```
diff --git a/README.md b/README.md
index 136d37b..1acf039 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,8 @@
-# BHTB-MIM-12-W20-DVCS
\ No newline at end of file
+# BHTB-MIM-12-W20-DVCS
+
+Schritte:
+
+`git clone https://github.com/kevinskyba/BHTB-MIM-12-W20-DVCS.git`
+`git add .`
+`git commit -m "Added new steps"`
+`git push`
\ No newline at end of file
```
`git add README.md`
`git commit -m "Added results of diffing"`
`git push`


---


`git branch some-feature`
`git checkout some-feature`
`echo test > test.txt`
`git add .`
`git commit -m "Added test.txt to some-feature branch"`
`git push`


---


`git checkout main`
`git merge some-feature`
`git add .`
`git commit -m "Added results of merging"`
`git push`