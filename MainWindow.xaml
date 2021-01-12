using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows;
using System.Windows.Controls;
using System.Windows.Data;
using System.Windows.Documents;
using System.Windows.Input;
using System.Windows.Media;
using System.Windows.Media.Imaging;
using System.Windows.Navigation;
using System.Windows.Shapes;

namespace Programme_Income_Calculate
{
    /// <summary>
    /// Interaction logic for MainWindow.xaml
    /// </summary>
    public partial class MainWindow : Window
    {
        public MainWindow()
        {
            InitializeComponent();
        }

        private void txtIncome_TextChanged(object sender, TextChangedEventArgs e)
        {
            
        }

        private void txtExpenses_TextChanged(object sender, TextChangedEventArgs e)
        {
            
        }

        private void txtNeed_TextChanged(object sender, TextChangedEventArgs e)
        {

        }

        private void txtSaving_TextChanged(object sender, TextChangedEventArgs e)
        {

        }

        private void Button_Click(object sender, RoutedEventArgs e)
        {
            double Total = double.Parse(txtNeed.Text) / (double.Parse(txtIncome.Text) - double.Parse(txtExpenses.Text));
            MessageBox.Show(" Done ");
            txtSaving.Text = Total.ToString(); 
        }


    }
}
