# reading_solution_files-freefem
reading solution files saved by freefem program

# freefemの計算結果をfreefemで読み込んで解析する

#メッシュを読み込んで表示

:show_mesh_poisson.edp

![Th-mesh-poisson](https://user-images.githubusercontent.com/1296728/223427532-685b816f-3f5a-482a-9d38-6b7d7dcebf05.jpg)

# 計算し、結果を保存する

:poisson-freefem.edp

# 保存した結果をfreefemで読み込み有限要素解としてメモリー上に再構築

:read_solution_poisson.edp

![poisson-freefem-sol](https://user-images.githubusercontent.com/1296728/223427786-db076877-f4cc-4d51-87cf-262b2f963f92.jpg)
