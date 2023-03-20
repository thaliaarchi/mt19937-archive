# MT19937 Archive

This is a reconstructed revision history for the MT19937 Mersenne Twister
pseudorandom number generator by Makoto Matsumoto and Takuji Nishimura.

It combines files from [Matsumoto's](https://web.archive.org/web/20050404003059/http://www.math.keio.ac.jp/matumoto/emt.html)
and [Nishimura's](https://web.archive.org/web/20020804170007/http://www.math.keio.ac.jp/~nisimura/random/)
archived sites at Keio University and [Matsumoto's current site](https://www.math.sci.hiroshima-u.ac.jp/m-mat/MT/emt.html)
at Hiroshima University. The two authors made changes independently with many
changes not being incorporated by the other author. Later changes appear to have
been made by Nishimura. I have carefully merged them into a cohesive history.
The script used to generate this repo is available in the
[repo-archival project](https://github.com/thaliaarchi/repo-archival/tree/main/scripts/mt19937).

Some snapshots were not archived, but were indicated by timestamps in directory
listings. I have inferred missing revisions from analogous changes and marked
these with `~` by the filename in `git log`.

See [readme-mt.txt](readme-mt.txt) for documentation and usage instructions.

Releases are tagged:
- [mt19937-1998](https://github.com/thaliaarchi/mt19937-archive/tree/mt19937-1998):
  The first standard version (1998-04-09)
  [[Matsumoto](https://www.math.sci.hiroshima-u.ac.jp/m-mat/MT/VERSIONS/C-LANG/ver980409.html)]
- [mt19937-1999](https://github.com/thaliaarchi/mt19937-archive/tree/mt19937-1999):
  The second standard version (1999-10-29)
  [[Matsumoto](https://www.math.sci.hiroshima-u.ac.jp/m-mat/MT/VERSIONS/C-LANG/ver991029.html)]
- [mt19937ar-2002](https://github.com/thaliaarchi/mt19937-archive/tree/mt19937ar-2002):
  Improved initialization (2002)
  [[Matsumoto](https://www.math.sci.hiroshima-u.ac.jp/m-mat/MT/MT2002/emt19937ar.html)]
