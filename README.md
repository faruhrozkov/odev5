Pytest dekoratörleri, Pytest test çerçevesindeki testlere ve test işlevlerine ekstra işlevsellik veya davranış eklemenin bir yoludur. Yaygın olarak kullanılan bazı Pytest dekoratörleri şunları içerir:

1 @pytest.fixture: Bu dekoratör, bir işlevi, diğer testlere veya fikstürlere veri veya kaynak sağlamak için kullanılabilen bir fikstür olarak işaretler. Fikstürler modül, sınıf veya fonksiyon seviyesinde tanımlanabilir.

@pytest.mark.parametrize: Bu dekoratör, aynı test kodunu farklı giriş değerleriyle çalıştırarak testleri parametrelendirmenize izin verir. Farklı senaryoları veya uç durumları test etmek için kullanılabilir.

@pytest.mark.skip: Bu dekoratör, henüz uygulanmadıkları veya başarısız oldukları bilindiği için bir testi veya test grubunu atlıyor.

@pytest.mark.xfail: Bu dekoratör, bilinen bir sorun olduğu veya bir hata koşulu için test ettiği için bir testi başarısız olması bekleniyor olarak işaretler.

@pytest.mark.timeout: Bu dekoratör, bir test için bir zaman aşımı belirler ve çalışması belirli bir süreden daha uzun sürerse testi iptal eder.

@pytest.mark.usefixtures: Bu dekoratör, test işlevi yürütülmeden önce fikstür işlevinin çağrılmasını sağlayarak bir teste bir fikstür uygular.

@pytest.mark.filterwarnings: Bu dekoratör, test çıktısındaki uyarı mesajlarını filtreleyerek ilgili test sonuçlarının tanımlanmasını kolaylaştırır.

Bu dekoratörler ve onlar gibi diğerleri, Pytest testlerinin davranışını özelleştirmek ve onları daha güçlü ve esnek hale getirmek için kullanılabilir.
