# Life-is-game
My first work is a bit too amateur
using System.Xml.Serialization;

namespace adma
{
    public partial class Saglık : Form
    {

        int saglık = 100;
        int yas = 0;
        int yıl = 2024;
        int para = 0;
        int zeka = 10;
        int guc = 10;
        int guzellik = 10;
        int akılsaglıgı = 50;
        Random rnd = new Random();




        public Saglık()
        {
            InitializeComponent();
        }
        private void gucluluk()
        {
            if (yas == 10)
            {


                int gucsans = rnd.Next(0, 3);
                if (gucsans == 1)
                {
                    guc = guc + 60;
                    Haberler.Items.Add("Güçlü bir çocuksun");
                }
                if (gucsans == 2)
                {
                    guc = guc + 30;
                    Haberler.Items.Add("sıska bir çocuksun");
                }
                if (gucsans == 3)
                {
                    guc = guc + 30;
                    Haberler.Items.Add("sıska bir çocuksun");
                }
            }
        }
        private void guzel()
        {
            if (yas == 15)
            {
                int guzelsans = rnd.Next(0, 3);
                if (guzelsans == 1)
                {

                    guzellik = guzellik + 60;
                    Haberler.Items.Add("güzel bir çocuksun +60 güzellik");
                }
                if (guzelsans == 4)
                {

                    guzellik = guzellik + 60;
                    Haberler.Items.Add("güzel bir çocuksun +60 güzellik");
                }
                if (guzelsans == 3)
                {

                    guzellik = guzellik + 40;
                    Haberler.Items.Add("güzel bir çocuksun +60 güzellik");
                }
                if (guzelsans == 2)
                {

                    guzellik = guzellik + 40;
                    Haberler.Items.Add("Ortalama güzellikte bir çocuksun +40 güzellik");
                }
            }
        }








        private void yasatla()
        {
            yas++;
            yıl++;
            textBoxyas.Text = Convert.ToString(yas);
            Tursay.Text = Convert.ToString(yıl);

        }
        private void yaslilik()
        {
            if (yas == 30)
            {
                saglık = saglık - 5;
                Haberler.Items.Add("yetişkin oldun");
                Haberler.Items.Add("");
            }
            if (yas == 45)
            {
                Haberler.Items.Add("yaslılık zor");
                Haberler.Items.Add("");
                saglık = saglık - 10;
            }
            if (yas == 65)
            {
                Haberler.Items.Add("yaslı olmaz cok zor");
                Haberler.Items.Add("");
                saglık = saglık - 20;
            }

            if (yas == 100)
            {
                Haberler.Items.Add("Lütfen öl artık");
                Haberler.Items.Add("");
                saglık = saglık - 20;
                akılsaglıgı = akılsaglıgı - 30;
            }
            if (yas == 110)
            {
                Haberler.Items.Add("öl");
                Haberler.Items.Add("");
                saglık = saglık - 20;
            }
            if (yas == 120)
            {
                Haberler.Items.Add("öl");
                Haberler.Items.Add("");
                saglık = saglık - 20;
            }


        }
        private void oldun()
        {
            if (saglık <= 0)
            {


                Close();

            }
        }
        private void gripoldun()
        {
            saglık = saglık - 5;
            Haberler.Items.Add("Grip oldun sağlığın azaldı");
            Haberler.Items.Add("");
        }

        private void hayat()
        {
            int yasam = 0;
            yasam = rnd.Next(1, 20);
            if (yasam == 1)
            {
                gripoldun();

            }
            if (yasam == 2)
            {
                arabakazası();
            }
            if (yasam == 3)
            {
                adayak();
            }
            if (yasam == 4)
            {
                doktor();
            }
            if (yasam == 5)
            {
                int kansersans = rnd.Next(1, 5);
                if (kansersans == 3)
                {
                    kanser();
                }

            }
            if (yasam == 6)
            {
                arkadas();
            }

        }
        private void yazdır()
        {
            textBoxGüzellik.Text = Convert.ToString(guzellik);
            textBoxZeka.Text = Convert.ToString(zeka);
            textBoxGuc.Text = Convert.ToString(guc);
            sağlık.Text = Convert.ToString(saglık);
            textBoxPara.Text = Convert.ToString(para);
            TextAkılsag.Text = Convert.ToString(akılsaglıgı);
            Haberler.Items.Add("Büyüdün ve yaşındasın");
            Haberler.Items.Add(yas);
        }
        private void sizofren()
        {
            if (yas > 40)
            {
                if (akılsaglıgı < 30)
                {
                    Haberler.Items.Add("olamaz Akıl sağlığını kaybediyorsun ŞİZOFRENİ BAŞLADI");
                    int akılsans = rnd.Next(1, 3);
                    if (akılsans == 2) {
                        akılsaglıgı = akılsaglıgı + 10;
                    }
                    else
                    {
                        Haberler.Items.Add("kafayı sıyırıyorsun sağlığın azaldı");
                        Haberler.Items.Add("WOLOLOWLOLOWLOLO");
                        saglık = saglık - 5;
                    }

                }
            }
        }
        
        private void okul()
        {
            if (yas >= 6 & yas <= 10)
            {
                zeka = zeka + 5;
                Haberler.Items.Add("ilkokuldasın Zekan 5 arttı");
                akılsaglıgı = akılsaglıgı + 5;
            }

            if (yas >= 10 & yas <= 14)
            {
                int sans;
                sans = rnd.Next(1, 3);
                if (sans == 1)
                {
                    Haberler.Items.Add("Ortaokuldasın başarılı oldun zekan 5 arttı");
                    zeka = zeka + 5;
                    akılsaglıgı = akılsaglıgı + 5;


                }
                if (sans == 2)
                {
                    Haberler.Items.Add("Ortaokuldasın başarısız oldun zekan 5 azaldı");
                    zeka = zeka - 5;

                }


            }
            if (yas >= 15 & yas <= 19)
            {

                if (zeka >= 50)
                {
                    Haberler.Items.Add("iyi bir liseye gittin");
                    int lisesans;
                    lisesans = rnd.Next(1, 3);
                    if ((lisesans == 1))
                    {
                        Haberler.Items.Add("bu yılı çok başarılı bitirdin ve lisedesin");
                        akılsaglıgı = akılsaglıgı + 5;
                        zeka = zeka + 10;

                    }
                    if ((lisesans == 2))
                    {
                        Haberler.Items.Add("bu yılı başarılı bitirdin ve lisedesin");
                        zeka = zeka + 5;
                    }
                }
                else
                {
                    int lisesans;
                    lisesans = rnd.Next(1, 3);
                    if ((lisesans == 1))
                    {
                        Haberler.Items.Add("bu yılı başarılı bitirdin ve lisedesin");
                        akılsaglıgı = akılsaglıgı + 5;
                        zeka = zeka + 5;

                    }
                    if ((lisesans == 2))
                    {
                        Haberler.Items.Add("bu yılı başarısız bitirdin ve lisedesin");
                        zeka = zeka + 10;
                    }
                }

            }
        }
        private void arkadas()
        {
            Haberler.Items.Add("arkadaşların sana hediye aldı +10 akıl sağlığı");

        }

        private void kanser()
        {
            Haberler.Items.Add("kanser oldun sağlığın ve güzelliğin 40 azaldı");
            saglık = saglık - 40;
            guzellik = guzellik - 40;
            akılsaglıgı = akılsaglıgı - 50;

        }
        private void adayak()
        {
            if (guc < 60)
            {
                Haberler.Items.Add("sokakta dayak yedin sağlık ve güzelliğin 5 azaldı");
                saglık = saglık - 5;
                guzellik = guzellik - 5;
                akılsaglıgı = akılsaglıgı - 20;

            }
        }
        private void doktor()
        {
            Haberler.Items.Add("doktora gittin sağlığın 10 arttı");
            saglık = saglık + 10;
            akılsaglıgı = akılsaglıgı + 5;


        }

        private void arabakazası()
        {
            Haberler.Items.Add("araba kazası geçridin sağlığın 20 azaldı ve çirkinleştin");
            saglık = saglık - 20;
            guzellik = guzellik - 10;
            akılsaglıgı = akılsaglıgı - 20;
        }
        private void button1_Click(object sender, EventArgs e)
        {

            if (saglık <= 1)
            {
                oldun();

            }
            else
            {
                yasatla();
                yaslilik();
                hayat();
                yazdır();
                okul();
                guzel();
                gucluluk();
                sizofren();

            }

        }

        private void Tursay_TextChanged(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {

        }

        private void textBoxyas_TextChanged(object sender, EventArgs e)
        {

        }

        private void label8_Click(object sender, EventArgs e)
        {

        }

        private void buttonOnayla_Click(object sender, EventArgs e)
        {

        }

        private void buttonReddet_Click(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged_1(object sender, EventArgs e)
        {

        }
    }
}

