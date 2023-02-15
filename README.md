# Simple_Crud-Rest-API
You can easly develop REST API CRUD use for PHP and MySQL. This tutorial will support you write and learn the way to develop REST API with PHP and MySQL from the basics and test the API using the postman app.       
                                              Steps:1
1. Create a database named apicruddb.
2. Create employee table
            
CREATE TABLE IF NOT EXISTS `Employee` (
`id` int(11) NOT NULL AUTO_INCREMENT,
`name` varchar(256) NOT NULL,
`email` varchar(50),
`designation` varchar(255) NOT NULL,
`created` datetime NOT NULL,
PRIMARY KEY (`id`)
)ENGINE=InnoDB DEFAULT CHARSET=utf8 AUTO_INCREMENT=19;
                                              Insert data
		
INSERT INTO `Employee` (`id`, `name`, `email`, `designation`, `created`) VALUES
(1, 'Rahul', 'rohit@gmail.com', 'Data Scientist', '2012-06-01 02:12:30'),
(2, 'Archana', 'archana1996@yahoo.com', 'Apparel Patternmaker', '2013-03-03 01:20:10'),
(3, 'pinal', 'pinal@gmail.com', 'Accountant', '2014-09-20 03:10:25'),
(4, 'Rahul', 'rahul2004@yahoo.com', 'Shipping Manager', '2015-04-11 04:11:12'),
(5, 'Rohit', 'rohitl7@gmail.com', 'Chief Sustainability Officer', '2016-01-04 05:20:30'),
(6, 'Ram', 'ram@hotmail.com', 'Chemical Technician', '2017-01-10 06:40:10'),
(7, 'samcurran', 'samcurran.may@yahoo.com', 'Transportation Planner', '2017-05-02 02:20:30'),
(8, 'Root', 'root@yahoo.com', 'Wind Energy Engineer', '2018-01-04 05:15:35'),
(9, 'andrew flower', 'andrew_roh@hotmail.com', 'Geneticist', '2019-01-02 02:20:30'),
(10, 'saymondas', 'saymondas@hotmail.com', 'Space Sciences Teacher', '2020-02-01 06:22:50');	

                                              Create a project folder named apicrudphp.
                                              Create api folder under the project folder.
                                              Create database.php with the following code in the project folder.
																							
