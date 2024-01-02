public class LoginScreen extends JFrame {
    public static void main(String[] args) {
        LoginScreen loginScreen = new LoginScreen();
        loginScreen.initializer();
    }

    final private Font BoldFont = new Font("Times New Roman", Font.BOLD, 24);
    final private Font mainFont = new Font("Times New Roman", Font.PLAIN, 12);

    public void initializer() {
        setTitle("GUUF IT DepartmentApp");
        setDefaultCloseOperation(WindowConstants.DISPOSE_ON_CLOSE);
        setSize(600, 600);
        setMaximumSize(new Dimension(350, 450));
        setLocationRelativeTo(null);
        JLabel WelcomeMessage = new JLabel("Welcome", SwingConstants.CENTER);
        WelcomeMessage.setFont(BoldFont);

        JLabel UsernameTXT = new JLabel("Username");
        UsernameTXT.setFont(mainFont);
        JTextField Username = new JTextField();
        Username.setFont(mainFont);

        JLabel PasswordTXT = new JLabel("Password");
        PasswordTXT.setFont(mainFont);
        JTextField Password = new JTextField();
        Password.setFont(mainFont);

        JPanel formPanel = new JPanel();
        formPanel.setLayout(new GridLayout(0, 1, 10, 10));
        formPanel.add(WelcomeMessage);
        formPanel.add(UsernameTXT);
        formPanel.add(Username);
        formPanel.add(PasswordTXT);
        formPanel.add(Password);

        add(formPanel);
        ImageIcon icon = new ImageIcon("src\\channels4_profile.png");
        setIconImage(icon.getImage());
        setVisible(true);
    }
}
