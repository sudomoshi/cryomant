```cs
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Diagnostics;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace enforcd
{
    public partial class About : Form
    {
        public About()
        {
            InitializeComponent();
        }

  

        private void AboutMe(object sender, EventArgs e)
        {

            MessageBox.Show("Location: United States")
                
            
        }

        private void MethodScroll_MouseHover(object sender, EventArgs e)
        {
            guna2HtmlToolTip1.Show("Your Text", MethodScroll);
            int r, g, b;
            r = 20;
            g = 20;
            b = 20;
            guna2HtmlToolTip1.BackColor = Color.FromArgb(r, g, b);
        }
    }
}
