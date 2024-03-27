<Window x:Class="sudoku.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:sudoku"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <TabControl>
        <TabItem Header="4x4">
            <UniformGrid>
                <UniformGrid >
                    <Button Click="Button_Click"></Button>
                    <Button Click="Button_Click_1"></Button>
                    <Button Click="Button_Click_2"></Button>
                    <Button Click="Button_Click_3"></Button>
                </UniformGrid>
                <UniformGrid >
                    <Button Click="Button_Click_4"></Button>
                    <Button Click="Button_Click_5"></Button>
                    <Button Click="Button_Click_6"></Button>
                    <Button Click="Button_Click_7"></Button>
                </UniformGrid>
                <UniformGrid >
                    <Button Click="Button_Click_8"></Button>
                    <Button Click="Button_Click_9"></Button>
                    <Button Click="Button_Click_10"></Button>
                    <Button Click="Button_Click_11"></Button>
                </UniformGrid>
                <UniformGrid >
                    <Button Click="Button_Click_12"></Button>
                    <Button Click="Button_Click_13"></Button>
                    <Button Click="Button_Click_14"></Button>
                    <Button Click="Button_Click_15"></Button>
                </UniformGrid>
            </UniformGrid>
        </TabItem>
    </TabControl>
</Window>


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

namespace sudoku
{
   
    public partial class MainWindow : Window
    {
        public MainWindow()
        {
            InitializeComponent();
        }

        private void Button_Click(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());
                
                if(ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_1(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_2(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_3(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_4(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_5(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_6(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_7(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_8(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_9(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_10(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_11(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_12(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_13(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_14(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }

        private void Button_Click_15(object sender, RoutedEventArgs e)
        {
            Button button = (Button)sender;
            if (button.Content == null)
            {
                button.Content = "1";
            }
            else
            {
                int ile = Int32.Parse(button.Content.ToString());

                if (ile == 4)
                {
                    ile = 1;
                }
                else
                {
                    ile++;
                }
                button.Content = ile.ToString();
            }
        }
    }
}
