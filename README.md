#Pitanje 1.:
Nakon dodavanja class library reference u Bin/Debug folderu sada se nalazi i ClassLibrary1.dll te ClassLibrary1.pdb.
Brisanjem ClassLibrary1 program se ne izvršava kako bi trebao, odnosno baca iznimku jer ne može pristupiti klasi koju koristimo u glavnom programu.
Pri slanju aplikacije uz .exe potrebno je poslati sve .dll datoteke.

#Pitanje 2.:
Ispis će i dalje biti isti. Izmjenjivanjem class library projekta ali ne i njegovim kompajliranjem .dll datoteka ostat ce ista kao i prije.

#Pitanje 3.:
Build proces automatski obnavlja NuGet pakete. NodeTime direktorij se opet nalazi u packages direktoriju.