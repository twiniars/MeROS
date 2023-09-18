# MeROS: SysML-based Metamodel for ROS-based Systems

## How to create release in steps

1. Prepare source codes of MeROS documentation
2. Prepare poster svg file (if needed)
3. Prepare new enterprise architect MeROS profile (if needed)
4. Commit and push local repository
5. Compile MeROS documentation locally (e.g. with texstudio) to resultant pdf file. Change the pdf name to **meros-X-Y-Z-doc.pdf**, where X.Y.Z is the release number,
6. (If needed) Save svg poster (e.g. with inkscape) as pdf file **meros-X-Y-Z-poster-b0.pdf**, where X.Y.Z is the release number,
7. (If needed) Save enterprise architect MeROS profile as **meros-X-Y-Z-ea-profile.xml**, where X.Y.Z is the release number,
8. Create release and tag X.Y.Z
9. Upload new documents (documentation, poster, profile)
10. Modify Changlelog
11. Modify README.md to link to new documents
12. Pull repository on local PC
