# stash_unstash

## STASH (SAKLAMAK)
#### git stash, çalışan kopyanızda yaptığınız değişiklikleri geçici olarak rafa kaldırır (veya saklar), böylece başka bir şey üzerinde çalışabilir 
ve daha sonra geri dönüp bunları yeniden uygulayabilirsiniz. Bağlamı hızlı bir şekilde değiştirmeniz ve başka bir şey üzerinde çalışmanız gerekiyorsa, saklamak
kullanışlıdır.


#### git stash komutu, taahhüt(commit) edilmemiş değişikliklerinizi (hem aşamalı hem de aşamalı olmayan) alır, bunları daha sonra kullanmak üzere kaydeder
ve ardından bunları çalışan kopyanızdan geri alır.

Örneğin: bir değişiklik üzerinde çalışırken başka bir konu ile ilgili kritik bir sorun bildirildiğinde yapmakta olduğumuz işi yarım bırakıp yeni soruna odaklanmak zorunda kalabilirsiniz. Bu gibi durumlarda yeni sorun ile ilgilenmeye başlamak için önceki değişikliklerinizi kaybetmeden yeni ve temiz bir branch oluşturmalısınız. Yarım kalan değişiklikleri kayıt altına almak için git stash komutunu kullanmalısınız.
