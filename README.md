# 255-final
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApplication1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {
            public class User
            {
                string PUID;
                string firstname;
                string lastname;
                string email;


            }

            public class Student: User
            {
                bool studentView;
            }

            public class Faculty: User
            {
                bool facultyView;
            }

            public class Professor: Faculty
            {

            }

           public class TeachingAssistant: Faculty
           {

           }

            public class EventCoordinator: User
            {

            }

            public class Utility
            {
                   
            }

            public class Notification: Utility
            {

            }

            public class Filter: Utility
            {

            }

            public class Event
            {

            }

            public class Classes: Event
            {

            }

            public class Exams: Event
            {

            }
            
            public class Deadline: Event
            {

            }

            public class ExtraCurricular: Event
            {

            }

            public class Day
            {

            }
            
        }
    }
}
