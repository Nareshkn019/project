# project
Two numbers (+,-,×,/)




﻿using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;


namespace arthamatic
{
    public partial class Form1 : Form
    {
        string a, b;
        int x, y;
        int c;
        
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

         private void button6_Click(object sender, EventArgs e)
        {
             a = textBox4.Text;
        b = textBox5.Text;
        x =Int32.Parse(a);
        y = Int32.Parse(b);
            c = x + y;
            textBox6.Text = Convert.ToString(c);
        }

        private void button7_Click(object sender, EventArgs e)
        {
        a = textBox4.Text;
        b = textBox5.Text;
        x =Int32.Parse(a);
        y = Int32.Parse(b);
            c = x - y;
            textBox6.Text = Convert.ToString(c);
        }

        


      

        private void button8_Click_1(object sender, EventArgs e)
        {
            a = textBox4.Text;
            b = textBox5.Text;
            x = Int32.Parse(a);
            y = Int32.Parse(b);
            c = x * y;
            textBox6.Text = Convert.ToString(c);
        }

        private void button9_Click_1(object sender, EventArgs e)
        {
            a = textBox4.Text;
            b = textBox5.Text;
            x = Int32.Parse(a);
            y = Int32.Parse(b);
            c = x / y;
            textBox6.Text = Convert.ToString(c);
        }

       

        
        }        
    }
