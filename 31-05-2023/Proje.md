
# 1-)Employees tablosundaki iş unvanı 'Programcı' olan tüm çalışanların çalışan ID'sini, adını ve soyadını getirin.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/bf8cda68-9f1a-43bd-9d96-2525617ceeca)
# 2-)Departments tablosundaki konum ID'si 1700 olan tüm departmanların departman ID'sini, departman adını ve yönetici ID'sini getirin.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/afc93d81-7af6-4f7b-804d-c5356d6ed01b)
# 3-)Jobs tablosundaki maksimum maaşı $10,000'den büyük olan işlerin iş ID'sini, iş unvanını ve maksimum maaşı getirin.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/a4468034-4705-4200-ab6a-69f9c81f40d3)

DIKKAT! : Asagidaki sorulari yazmadan once CTAS kullanarak tablolarin back up ini olusturup o kopya uzerinden testlerinizi yazin. Aksi halde orjinal tablo yapisini kaybedeceginizden onumuzdeki derslerde yazacaginiz queryler calismayabilir!!!
Alttaki Soru 4 icin Ornek : create table employees_bckp as ( select * from hr.employees)) dedikten sonra employees_bckp tablsounda sutun adi degistirme islemini yapin.

# 4-) "employees" tablosundaki "job_id" sütununun adını "position_id" olarak değiştirin. (AS kullanımı)
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/c4bd74e9-4f74-48b3-becf-21c2b3bfe4cb)

# 5-) "employees" tablosundaki "salary" sütununun veri tipini NUMBER(10, 2)'den NUMBER(12, 2)'ye değiştirin. (Alter)
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/91a93030-5441-4ba8-ab76-5deeb3f3c9ca)

# 6-) "departments" tablosundaki "department_name" sütununun adını "dept_name" olarak değiştirin.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/d1878383-a496-4675-b8d8-2486c38f9415)

# 7-) Oncelikle database uzerinde ‘test_user’ isimli bir kullanici yaratin.
"employees" tablosunda "full_name" sütununa SELECT iznini "test_user" kullanıcısına verin.
"employees" tablosunda "salary" sütunundaki INSERT iznini "test_user"

Yeni bir sekmede test_user ile login olmayi deneyip employees de select ve insert yapip yapamadiginizi test edin.

# 8-) "employees" tablosunda "salary" sütunundaki INSERT iznini "test_user" kullanıcısından geri alın. sonucu test edin

# 9-) "employees" tablosundan yeni bir yedek tablo oluşturun ve bu tablo sadece "employee_id", "first_name" ve "last_name" sütunlarını içersin ve sadece tablo yapisini alsin. Icinde data / satir olmasin.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/445af116-209e-417f-8f58-06e0e610d35b)

# 10-) "employees" tablosunda yer alan "hire_date" adlı tarih sütunundaki yılların sadece son iki hanesini alarak yeni bir table ve sütuna kaydeden bir CTAS sorgusu oluşturun.

# 11-) Sehirler isimli 5 kolondan olusan bir tablo yaratin. Tablonun ozellikleri :
Plaka Kodu – 2 Karakter Sabit – Primary Key ve Bos olamaz
Sehir Adi – Degisken 20 Karakter – Bos olamaz
Yuz olcumu – Degisken 10 Karakter Sayi 2 Karatker Kusurat olabilir – Bos olabilir
Nufus – Degisken 10 Karakter Sayi – Bos olabilir
Bolge – 2 Karakter sabit – Bos olamaz 
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/73fa3a88-bb18-486e-a377-5f064ebdfa11)

Sorular: 
Bu yarattiginiz tabloya 5 tane sehir biliginisi Insert statement kullanarak giriniz.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/ca5e8d10-9228-4d38-9c57-2c2a936a1522)

Bu girilen 5 sehiri tek bir SQL komutunda girecek sekilde modifiye ediniz. (Yani 5 kere Insert degil de 1 Insert statement la 5 satir veri girisi)
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/3b6b6152-95d6-4224-9488-1efdaac8f687)

Girilen sehirlerden istediginiz 1 tanesini siliniz (ipucu Delete from statement kullanarak)
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/60e841e1-3d40-4f0e-87c1-e5121d7b5ee6)

Kalan tablonun CTAS ile backup ini yaratip , yarattiginiz tablonun icindeki veriyi truncate ediniz.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/61608466-7cdf-41a6-93df-36fe11e2a01c)

# 12-) "SELECT" ifadesi ve "dual" tablosunu kullanarak ekrana "Merhaba, Dünya!" mesajını yazdıran bir sorgu yazın. 
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/f62d3150-cc7a-4b9e-9e55-b58c8a1354b1)

# 13-) Oracle Dual tablosundan suanki system saat bilgisini cekiniz.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/c11f4de7-8588-472a-b5a3-e79d1e8f32c2)

# 14-) "dual" tablosunu kullanarak iki sayının toplamını hesaplayan bir sorgu yazın.
![image](https://github.com/cengarm/SQL-Homework-Techcareer.net/assets/126611512/98d2f9af-11c8-4053-a64c-080590daa33f)

# 15-) substr fonksiyonu ve dual tablosunu kullanarak "Merhaba, Dünya!" yazinin ilk 7 karakterini ayni satir uzerinde "Merhaba, Dünya!" yazinin yaninda ilkkelime kolonunda gosteriniz.

