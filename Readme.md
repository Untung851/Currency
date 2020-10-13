#Currency Apps

aplikasi ini mencakup fungsi perhitungan nilai tukar mata uang dari dollar ke rupiah.satu dolar dianggap Rp.15.000

#Scope&functionalities

-user dapat memasukan angka

-user dapat menyentuh tombol hitung

-user mendapat info "INVALID" jika yang dimasukan berupa text

##How does is works?

Diawali dengan method mainwindows pada class mainwindows.xaml.cs

"""

       public MainWindow()
        {
            InitializeComponent();
            currency = new Currencycontroller();
        }
"""