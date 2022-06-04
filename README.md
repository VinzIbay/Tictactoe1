# Tictactoe1
namespace tictactoe
{
    public partial class Form1 : Form
    {
        bool turn = true; //true= X turn; false= Y turn
        int turn_count = 0;

        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }
private void gameToolStripMenuItem_Click(object sender, EventArgs e)
        {

        }
 private void gameToolStripMenuItem_Click(object sender, EventArgs e)
        {

        }

        private void aboutToolStripMenuItem_Click(object sender, EventArgs e)
        {
            MessageBox.Show("Made By Ibay", "Tic Tac Toe About");
        }

        private void exitGmeToolStripMenuItem_Click(object sender, EventArgs e)
        {
            Application.Exit();
        }

        private void button_Click(object sender, EventArgs e)
