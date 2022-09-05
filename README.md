# stash_unstash

## STASH (SAKLAMAK)
#### git stash, çalışan kopyanızda yaptığınız değişiklikleri geçici olarak rafa kaldırır (veya saklar), böylece başka bir şey üzerinde çalışabilir 
ve daha sonra geri dönüp bunları yeniden uygulayabilirsiniz. Bağlamı hızlı bir şekilde değiştirmeniz ve başka bir şey üzerinde çalışmanız gerekiyorsa, saklamak
kullanışlıdır.


#### git stash komutu, taahhüt(commit) edilmemiş değişikliklerinizi (hem aşamalı hem de aşamalı olmayan) alır, bunları daha sonra kullanmak üzere kaydeder
ve ardından bunları çalışan kopyanızdan geri alır.

Örneğin: bir değişiklik üzerinde çalışırken başka bir konu ile ilgili kritik bir sorun bildirildiğinde yapmakta olduğumuz işi yarım bırakıp yeni soruna odaklanmak zorunda kalabilirsiniz. Bu gibi durumlarda yeni sorun ile ilgilenmeye başlamak için önceki değişikliklerinizi kaybetmeden yeni ve temiz bir branch oluşturmalısınız. Yarım kalan değişiklikleri kayıt altına almak için git stash komutunu kullanmalısınız.

![stash](https://user-images.githubusercontent.com/81867200/188406729-5c57b1f0-25b1-460b-8e1c-f1af044fe7f0.png)

Bir diğer branch'de yaptığımız modifiye edilmiş dosyayı main branch'imizde kullanmak istendiğimizde stash etmemiz gerektiğini söyleyen bir uyarı alırız.


![stash2](https://user-images.githubusercontent.com/81867200/188412880-b53c9aeb-2364-47c8-b8ea-cc9ac8c5b8da.png)
Git stash save yaptığımızda yaptğımız değişikliği local repositoryimize işlemiyoruz farklı bir yerde işlenmek üzere bekletiyoruz.

git stash list komutu ile stash'lerimizin listesine ulaşabilirz.

##### git stash -p "id" komutu çalıştırdğımızda yaptığımız değişikliği gösterir.
not: en son yapılan değişiklik id=0 ile gelir.

![stashpop](https://user-images.githubusercontent.com/81867200/188413565-957af455-72a9-442d-a1ff-97f0de39e6fd.png)
#### git stash pop komutu stash'imizi uygular ve dosyaları zuladan kaldırır. 


![stashapply](https://user-images.githubusercontent.com/81867200/188414455-c8fe436f-355a-4e01-a987-999929755fa1.png)
#### git stash apply komutu değişiklikleri uygular ve stash'in bir kopyasını bırakır


