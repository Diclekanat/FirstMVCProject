ASP.Net(.Net Framework) C# olan app i seçelim.
--MVC (Model-View-Controller)--
Model-View-Controller

Deneme Controller ına View eklemek için Deneme metoduna sağ tık yapıp Add View seçilir. 

Açılan pencerede adım adım View-Add-Layout Page-Shared-Layout.html yapıldı ve Layout.html seçildi. 

                    <li>@Html.ActionLink("Anasayfa", "Index", "Home")</li>
Burada parantez içerisindeki değişkenlerin özellikleri;
1.Butonun ismi ()
2.Controller içindeki metodun adı
3.View içindeki hangi klasörde olduğunu belirtir (Dosya adı) 


                    <li>@Html.ActionLink("Deneme", "Deneme", "Home")</li>
Views-Shared-Layout.cshtml içerisinde body kısmına yeni bir kod ekleyerek Deneme sayfası oluşturuldu.

Test sayfası oluşturuldu. Test sayfası Layout Page e eklendi.

Yeni bir Layout Page oluşturuldu. Layout Page işçierisine diğper sayıların hangi alanda görüntüleneceğini belirtmek için 
@RenderBody kodu kullanıldı.

Yeni bir Layout için Shared folder ına sağ click yapılıp Add-Controller-View-seçildi. Yeni bir DenemeLayout oluşturuldu.
Oluşan yeni layout Page e Body içerisinde yeni bir div açıp @RenderBody() kodu yazıldı.

Solution-Add-New Project-Class Library(.Net Framework)  C# Projemize 4 katman ekledik.
1)EntityLayer (Tablolar-->Class, Sütunlar-->Property)
2)DataAccessLayer (CRUD İşlemleri)
3)BusinessLayer ()
4)PresentationsLayer

------EntityLayer-----
Katmanın içine Concrete Klasörü oluşturuyoruz.
Oluşturulacak Tablolar
1)Writer(Yazar)
2)Category()
3)Heading()
4)Content
5)About
6)Contact()









