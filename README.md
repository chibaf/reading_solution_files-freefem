# reading_solution_files-freefem
reading solution files saved by freefem program

# freefemの計算結果をfreefemで読み込んで解析する

２次元のfreefemでも計算に数時間かかることはよくあります。そういう場合、結果を保存しfreefemで読み込めるようにしておくと、後の解析に便利です。

# メッシュを読み込んで表示

:show_mesh_poisson.edp

![Th-mesh-poisson](https://user-images.githubusercontent.com/1296728/223427532-685b816f-3f5a-482a-9d38-6b7d7dcebf05.jpg)

# 有限要素法で解を計算し、結果を保存する

:poisson-freefem.edp

![poisson_solution](https://user-images.githubusercontent.com/1296728/223429539-c9643dde-75db-4943-8c94-311432a9e292.jpg)

# 保存した結果をfreefemで読み込み有限要素解としてメモリー上に再構築

:read_solution_poisson.edp

![poisson-freefem-sol](https://user-images.githubusercontent.com/1296728/223427786-db076877-f4cc-4d51-87cf-262b2f963f92.jpg)

# 境界( $\Gamma_1$, $\Gamma_2$, $\Gamma_3$, $\Gamma_4$ )での解の値
