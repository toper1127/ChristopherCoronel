ChristopherCoronel
==================
<!doctype html>
<html>
<head>
	<title>LVCC Computer Programming 2nd Year</title>
	<link rel="stylesheet" href="color.css" />
</head>

<body>
<div id="wrap">
	<h1>LVCC Computer Programming 2nd Year</h1>
	<h6>Code &amp; Design by: Christopher Coronel &trade;</h6>

<?php

	$i = 1;

	$names = array(
				array(
					'#' => $i++,
					'firstname' => 'Reagan',
					'lastname' => 'Aguilar',
					'age' => '20 ',
					'birthday' => '1/25/1994',
					'email' => 'ezekiel_2501@yahoo.com',
					'contact' => '(+63) (935) 522-9627'
					),
				array(
					'#' => $i++,
					'firstname' => 'Joshua Genesis',
					'lastname' => 'Aquino',
					'age' => '21 ',
					'birthday' => '4/6/1993',
					'email' => 'josh_gen06@yahoo.com',
					'contact' => '(+63) (933) 249-9197'
					),
				array(
					'#' => $i++,
					'firstname' => 'Leah',
					'lastname' => 'Bacala',
					'age' => '25',
					'birthday' => '2/28/1989',
					'email' => 'leahbacala@gmail.com',
					'contact' => '(+63) (909) 354-6336'
					),
				array(
					'#' => $i++,
					'firstname' => 'Bryan',
					'lastname' => 'Capili',
					'age' => '21 ',
					'birthday' => '11/9/1992',
					'email' => 'bryancapili34@yahoo.com',
					'contact' => '(+63) (977) 168-7383'
					),
				array(
					'#' => $i++,
					'firstname' => 'Krisdel Joy',
					'lastname' => 'Catua',
					'age' => '23 ',
					'birthday' => '7/30/1990',
					'email' => 'krisdeljoycatua@gmail.com',
					'contact' => '(+63) (906) 689-6399'
					),
				array(
					'#' => $i++,
					'firstname' => 'Christopher',
					'lastname' => 'Coronel',
					'age' => '17 ',
					'birthday' => '7/31/1996',
					'email' => 'christopher_1127@yahoo.com',
					'contact' => '(+63) (927) 287-5928'
					),
				array(
					'#' => $i++,
					'firstname' => 'Arvin Carlo',
					'lastname' => 'Cris',
					'age' => '16 ',
					'birthday' => '9/22/1997',
					'email' => 'arvincarloramoscris@gmail.com',
					'contact' => '(+63) (948) 693-0038'
					),
				array(
					'#' => $i++,
					'firstname' => 'Franz Dale Noa',
					'lastname' => 'Cuneta',
					'age' => '17 ',
					'birthday' => '1/29/1997',
					'email' => 'dark_franz60@yahoo.com',
					'contact' => '(+63) (930) 597-8824'
					),
				array(
					'#' => $i++,
					'firstname' => 'Russell',
					'lastname' => 'De Vera',
					'age' => '17 ',
					'birthday' => '9/14/1996',
					'email' => 'redevera_alert67@yahoo.com',
					'contact' => '(+63) (912) 691-9575'
					),
				array(
					'#' => $i++,
					'firstname' => 'Jesson',
					'lastname' => 'Enriquez',
					'age' => '17 ',
					'birthday' => '9/14/1996',
					'email' => 'jesson.1495@gmail.com',
					'contact' => '(+63) (929) 329-5847'
					),
				array(
					'#' => $i++,
					'firstname' => 'Christian Andrew',
					'lastname' => 'Fabian',
					'age' => '17 ',
					'birthday' => '7/15/1996',
					'email' => 'andrew.fabian11@yahoo.com',
					'contact' => '(+63) (907) 481-0871'
					),
				array(
					'#' => $i++,
					'firstname' => 'El-Angelo',
					'lastname' => 'Ferrer',
					'age' => '18 ',
					'birthday' => '3/24/1996',
					'email' => 'tsubtsatagilidakeyn@yahoo.com',
					'contact' => '(+63) (933) 731-9781'
					),
				array(
					'#' => $i++,
					'firstname' => 'Shiela',
					'lastname' => 'Fuertes',
					'age' => '19 ',
					'birthday' => '1/19/1995',
					'email' => 'shiela.fuertes@yahoo.com',
					'contact' => '(+63) (930) 598-5676'
					),
				array(
					'#' => $i++,
					'firstname' => 'Andrea',
					'lastname' => 'Gallardo',
					'age' => '17 ',
					'birthday' => '11/30/1996',
					'email' => 'dhea.casil@yahoo.com.ph',
					'contact' => '(+63) (910) 447-8563'
					),
				array(
					'#' => $i++,
					'firstname' => 'Jerico',
					'lastname' => 'Garcia',
					'age' => '17 ',
					'birthday' => '1/22/1997',
					'email' => 'jherilyn_12297@gmail.com',
					'contact' => '(+63) (909) 355-0116'
					),
				array(
					'#' => $i++,
					'firstname' => 'Theresa Mahrie',
					'lastname' => 'Gardoce',
					'age' => '17 ',
					'birthday' => '3/13/1997',
					'email' => 'gardocet@yahoo.com',
					'contact' => '(+63) (910) 838-7823'
					),
				array(
					'#' => $i++,
					'firstname' => 'Rolyn',
					'lastname' => 'Janabajab',
					'age' => '20 ',
					'birthday' => '6/28/1994',
					'email' => 'rjanabajab@gmail.com',
					'contact' => '(+63) (905) 678-8973'
					),
				array(
					'#' => $i++,
					'firstname' => 'Maria Marcelina Lolita',
					'lastname' => 'Loyola',
					'age' => '16 ',
					'birthday' => '11/1/1997',
					'email' => 'celineloyola143@gmail.com',
					'contact' => '(+63) (948) 864-9768'
					),
				array(
					'#' => $i++,
					'firstname' => 'Ma. Cruzita',
					'lastname' => 'Macrohon',
					'age' => '17 ',
					'birthday' => '9/7/1996',
					'email' => 'sitaymacrohon@gmail.com',
					'contact' => '(+63) (926) 872-4817'
					),
				array(
					'#' => $i++,
					'firstname' => 'Abel',
					'lastname' => 'Malano',
					'age' => '24 ',
					'birthday' => '9/20/1989',
					'email' => 'abelmalano@gmail.com',
					'contact' => '(+63) (935) 847-6003'
					),
				array(
					'#' => $i++,
					'firstname' => 'Maria Lee',
					'lastname' => 'Malonzo',
					'age' => '23 ',
					'birthday' => '9/15/1990',
					'email' => 'mariel_malonzo@yahoo.com',
					'contact' => '(+63) (935) 875-2558'
					),
				array(
					'#' => $i++,
					'firstname' => 'Jordan',
					'lastname' => 'Marbella',
					'age' => '16 ',
					'birthday' => '10/29/1997',
					'email' => 'jay21129@yahoo.com',
					'contact' => '(+63) (916) 879-2578'
					),
				array(
					'#' => $i++,
					'firstname' => 'Arvin',
					'lastname' => 'Medina ',
					'age' => '17 ',
					'birthday' => '10/10/1996',
					'email' => 'arvinmedina2010@yahoo.com',
					'contact' => '(+63) (930) 599-6829'
					),
				array(
					'#' => $i++,
					'firstname' => 'Christopher',
					'lastname' => 'Monteron',
					'age' => '17 ',
					'birthday' => '11/24/1996',
					'email' => 'christopher.monteron_7@yahoo.com',
					'contact' => '(+63) (949) 629-1476'
					),
				array(
					'#' => $i++,
					'firstname' => 'Rachel',
					'lastname' => 'Quiambao',
					'age' => '17 ',
					'birthday' => '11/12/1996',
					'email' => 'quiambaorachel12@yahoo.com',
					'contact' => '(+63) (918) 775-3587'
					),
				array(
					'#' => $i++,
					'firstname' => 'Catherine',
					'lastname' => 'Rasci',
					'age' => '31 ',
					'birthday' => '10/20/1982',
					'email' => 'catherinemirandarasci@yahoo.com',
					'contact' => '(+63) (932) 790-2491'
					),
				array(
					'#' => $i++,
					'firstname' => 'Mark Lois',
					'lastname' => 'Razon',
					'age' => '18 ',
					'birthday' => '1/20/1996',
					'email' => 'loisrazon20@gmail.com',
					'contact' => '(+63) (916) 893-3122'
					),
				array(
					'#' => $i++,
					'firstname' => 'Manuel',
					'lastname' => 'Roscas',
					'age' => '19 ',
					'birthday' => '8/19/1994',
					'email' => 'roscasmanuel_19@yahoo.com',
					'contact' => '(+63) (907) 120-4184'
					),
				array(
					'#' => $i++,
					'firstname' => 'Ryugie',
					'lastname' => 'Tan',
					'age' => '17 ',
					'birthday' => '8/25/1996',
					'email' => 'tanryugie@yahoo.com',
					'contact' => '(+63) (907) 969-2727'
					),
				array(
					'#' => $i++,
					'firstname' => 'Renaldo',
					'lastname' => 'Valente',
					'age' => '31 ',
					'birthday' => '6/15/1983',
					'email' => 'arrowbrave@gmail.com',
					'contact' => '(+63) (933) 285-2493'
					),
				array(
					'#' => $i++,
					'firstname' => 'Rose Ann',
					'lastname' => 'Villar',
					'age' => '18 ',
					'birthday' => '6/16/1996',
					'email' => 'roseannvillar@ymail.com',
					'contact' => '(+63) (905) 764-7494'
					)
				);

	#firstname, last name, age, brthday, email, contact number

	echo '<table border="0" width="100%">';
	echo '<tr>';
	echo '<th width="15%">First Name</th>';
	echo '<th width="15%">Last Name</th>';
	echo '<th width="5%">Age</th>';
	echo '<th width="10%">Birthday</th>';
	echo '<th width="35%">Email</th>';
	echo '<th width="20%">Contact No.</th>';
	foreach($names as $name) {
		
		if ($name['lastname'] == 'Coronel') {
			echo '<tr class="toper">';
		} elseif ($name['#'] % 2 == 0) {
			echo '<tr class="row">';
		} else {
			echo '<tr>';
		}

		echo '<td>';
		echo $name['firstname'];
		echo '</td>';
		echo '<td>';
		echo $name['lastname'];
		echo '</td>';
		echo '<td>';
		echo $name['age'];
		echo '</td>';
		echo '<td>';
		echo $name['birthday'];
		echo '</td>';
		echo '<td>';
		echo $name['email'];
		echo '</td>';
		echo '<td>';
		echo $name['contact'];
		echo '</td>';
		echo '</tr>';
	}
	echo '</table>';

?>
		</div>
	</body>
</html>
_____________________________________________
Css

body {
	font-family: Bookman Old Style, sans-serif;
	font-size: 12pt;
	color: #111111;
	background-color: #1d609e;
}

#wrap {
	width: 100%;
	margin: 0 auto;
	text-align: center;
}

h1, h2, h3, h4, h5, h6 {
	margin: .2em;
	line-height: 1em;
}

table, td, tr, th {
	border: 0;
	margin: 1em 0;
}

table {
	border: 2px solid #333333;
	text-align: left;
}

th {
	background-color: #333333;
	color: #cccccc;
	font-family: Cooper Std Black;
	font-size: 1.2em;
	padding: 10px;
}

tr {
	background-color: #5b9bd5;
}

td {
	padding: 5px;
}

.row {
	background-color: #2f75b5;
}
tr:hover{
	background-color: #ffff00;
}
.toper {
	background-color: #cccccc;
	color: #333333;
}

.toper {
	font-weight: bold;
}

