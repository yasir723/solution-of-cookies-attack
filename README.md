# Solution of Cookies Attack

Bu saldırıyı anlatan sayfada gördüğümüz gibi, hackerlar çerezlerdeki parametreleri kullanarak hassas bilgileri ele geçirip oturum çalabiliyor. Bu sayfada, geliştirici olarak bu tür saldırılardan sistemimizi nasıl koruyabileceğimizi öğreneceğiz. Öncelikle, hiçbir durumda hassas bilgileri çerezler aracılığıyla göndermemeliyiz; bu, ciddi bir güvenlik açığı oluşturur. İleri düzey saldırılarda, hassas bilgilerin güvenli bir şekilde nasıl gönderilmesi gerektiği anlatılmıştır. Ancak bu sayfada, eğer hassas bilgileri göndermemiz gerekirse, bunu nasıl güvenli hale getirebileceğimiz üzerinde duracağız.

Örnek olarak kullandığımız web sitede giriş yaptıktan sonra hareket sayfasına gittiğimizde çerezlerde userName biglisini parametre olarak iletildiğini farkedeceğiz:

![username in cookies](https://github.com/user-attachments/assets/c5ec7e5f-16dd-40c9-a2c9-c34b83c61585)

