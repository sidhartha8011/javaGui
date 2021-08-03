## AMBULANCE BOOKING SYSTEM
A Advance Ambulance Booking Gui Java Project that can used to book an ambulance for remote areas.
The application takes patient information and guides him through differnt the areas in which the services are provided along with differnt hospitals we have tied up with followed by the payment screen, Where Total bill is calculated based on the location of services.

## Building Process

This project was build by two People me(sidhartha Parasramka) and my teammate(soumya Agrawal) as project to demonstrate our skills that we have mastered during our 2nd year in the college

We have used various advance concepts such as jawa swings that are widely used in the indusrty.
```markdown
Concepts used

-object orient programing
-Problem solving
-JAVA Swings

#A Peice of our code

public MyFrame() {
		
		super("AMBULANCE SERVICE PROVIDER");
		
		pinfo =new JPanel();
		pinfo.setBackground(SystemColor.white);
		service =new JPanel();
		service.setBackground(SystemColor.white);
		calculate =new JPanel();
		calculate.setBackground(SystemColor.white);
		hospital =new JPanel();
		hospital.setBackground(SystemColor.white);
		
		JTabbedPane tb = new JTabbedPane();
		
		
		submit= new JButton("SUBMIT");
		submit1= new JButton("SUBMIT");
		submit2= new JButton("NEXT");
		
		
		 JLabel lblNewLabel = new JLabel(" ambulance");
		 lblNewLabel.setIcon(new ImageIcon(ambulance.class.getResource("/java_project/p1.jpg")));
		 lblNewLabel.setBounds(5,5,969,272);
		 pinfo.add(lblNewLabel);
      
        
        
		tb.add("			        Patient Information            ",pinfo);
		tb.add("			        Service Availiability	       ",service);
		tb.add("			        Associated Hospitals           ",hospital);
		tb.add("			        Payment and bill              ",calculate);
		tb.setFont(new Font("Century Schoolbook", Font.BOLD, 14));
		add(tb);
		
		
		 //info panel
	 	 l1=new JLabel("Name");
	 	 l1.setFont(new Font("Copperplate Gothic Bold", Font.PLAIN, 14));
		 l2=new JLabel("Contact.NO");
		 l2.setFont(new Font("Copperplate Gothic Bold", Font.PLAIN, 14));
		 l3=new JLabel("Gender");
		 l3.setFont(new Font("Copperplate Gothic Bold", Font.PLAIN, 14));
		 l4=new JLabel("Pathology");
		 l4.setFont(new Font("Copperplate Gothic Bold", Font.PLAIN, 14));
		 l5=new JLabel("D.O. SERVICE");
		 l5.setFont(new Font("Copperplate Gothic Bold", Font.PLAIN, 14));
		 l6=new JLabel("Date  ");
		 l6.setFont(new Font("Arial Narrow", Font.PLAIN, 14));
		 
		 tf1=new JTextField("");
		 tf2=new JTextField("");
		 tf3=new JTextField("");
		 tf4=new JTextField("");
		
		 pinfo.setLayout(null);
		 tf1.setBounds(EXIT_ON_CLOSE, ABORT, WIDTH, HEIGHT);
		
		 bg1= new ButtonGroup();
		 c1=new JRadioButton("Male");
		 c2=new JRadioButton("Female");
		 bg1.add(c1);
		 bg1.add(c2);
```


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sidhartha8011/javaGui/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
