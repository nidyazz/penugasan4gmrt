# LeetCode 3331 - Find Subtree Sizes After Changes

Soal: https://leetcode.com/problems/find-subtree-sizes-after-changes/

## Ide solusi
- DFS iteratif dengan array `last[26]` untuk mencari leluhur terdekat
  yang hurufnya sama (di pohon asli).
- Ukuran subtree dihitung dengan reverse preorder.
- Kompleksitas: waktu O(n), memori O(n).

## Cara menjalankan
g++ -std=c++17 solution.cpp -o solution
./solution