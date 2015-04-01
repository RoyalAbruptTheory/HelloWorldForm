/*
# HelloWorldForm
School Project Form app created using Microsoft Visual Studio. Using a created company name and logo.
*/

using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Assn01_AuroiahMorgan
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void xDisplayButton_Click(object sender, EventArgs e)
        {
            xPictureLabel.Visible = true;
            xTitleLabel.Visible = true;
        }

        private void xClearButton_Click(object sender, EventArgs e)
        {
            xPictureLabel.Visible = false;
            xTitleLabel.Visible = false;
        }

        private void xExitButton_Click(object sender, EventArgs e)
        {
            this.Close();
        }
    }
}
