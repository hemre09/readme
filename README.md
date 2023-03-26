@pytest.fixture: Bu dekoratör, tablolar için gerekli olan düzenleme düzenlemesini sağlar. Bu yapı, test araçlarının parametrelerinde kullanılabilir. Örneğin, bir test işlevinde bir arşiv bağlantısı olması gerekir, bu dekoratörle bir fikstür işlevi oluşturulabilir ve bu işlev test işlevi parametresi olarak kullanılabilir.

@pytest.mark.parametrize: Bu dekoratör, bir test cihazlarını farklı kullanımlarıyla kullanmak için kullanılır. Bu dekoratörü kullandığınızda, bir dizi parametre belirleyip test öğelerini birden fazla kez çalıştırabilirsiniz. Bu, test kapsamını kullanır ve farklı senaryoları test etmeyi sağlar.

@pytest.mark.skip: Bu dekoratör, belirli bir testin geçici olarak atılmasını sağlar. Bu dekoratörü kullanarak, bir testin geçici olarak devre dışı bırakılmasını ve daha sonra geri ayarının yeniden etkinleştirilmesini sağlayabilirsiniz.

@pytest.mark.xfail: Bu dekoratör, bir testin alıcı olması beklenen bir senaryoda kullanılır. Bu dekoratörü kullanırken, testin başarısız olmasına rağmen hala çalıştırılmasını sağlayabilirsiniz. Bu, bir hata durumunda bile testin devam süreçlerini ve sonlarını sağlar.

@pytest.mark.timeout: Bu dekoratör, bir testin belirli bir süre içinde tamamlanmasını sağlar. Bu dekoratörü kullanarak, bir testin belirli bir sürede tamamlanması durumunda hata mesajı oluşturabilirsiniz.

@pytest.mark.flaky: Bu dekoratör, bir testin belirli bir sayısı başarısız denemeden sonra başarılı olmasını sağlar. Bu dekoratörü kullanarak, bir testin belirli bir süre veya deneme sayısında başarılı olmasını sağlamak için kullanılır.
