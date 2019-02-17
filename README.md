# sandbox
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Candy FM Giveaway</title>
		<meta name="viewport" content="initial-scale=1.0, width=device-width">
		<link href="https://fonts.googleapis.com/css?family=Major+Mono+Display|Oswald|Roboto" rel="stylesheet">
	</head>
	<body>
		<header>
			<h1>Candy FM Giveaway!</h1>
			<p>Three our listeners who will answer the questions correctly will win pairs of tickets to the selected concert!</p>
		</header>
		<form id="survey-form">
			<!-- user info-->
			<div class="question-block-width">
			<div class="all-question-blocks first-block">
				<div class="user-info">
					<div class="label">
						<label id="name-label" for="name">*Name: </label>
					</div>
					<div class="input-field">
						<input id="name-label" type="text" name="name" placeholder="Enter your name" required>
					</div>
				</div>
				<div class="user-info">
					<div class="label label-user">
						<label id="email-label" for="name">*E-mail: </label>
					</div>
					<div class="input-field">
						<input id="email-label" type="email" name="email" placeholder="Enter your e-mail" required>
					</div>
				</div>
				<div class="user-info">
					<div class="label label-user">
						<label id="number-label" for="age">*Age: </label>
					</div>
					<div class="input-field">
						<input id="number-label" type="number" name="age" class="input-field" placeholder="18-125" min="1" max="125" required>
					</div>
				</div>
			</div>
			<!-- drop text-->
			<div class="button-placement">
				<div class="all-question-blocks">
					<div class="questions">
						<div class="q-block">
							<div class="label">
								<label for="dropdown" class="label">*Which of the bands won the most Grammy awards?</label>
							</div>
							<div>
								<select id="dropdown" name="style" required>
									<option value="rolling-stones">The Rolling Stones</option>
									<option value="muse">Muse</option>
									<option value="queen">Queen</option>
									<option value="red-hot-chilli">Red Hot Chilli Peppers</option>
								</select>
							</div>
						</div>
						<div class="q-block">
							<div class="label">
								<label for="radio">*Which of the following pop artists sold the most records?</label>
							</div>
							<div>
								<ul>
									<li><label class="label"><input id="1" type="radio" name="radio" value="beyonce" required>Beyonce</label></li>
									<li><label class="label"><input id="2" type="radio" name="radio" value="gaga">Lady Gaga</label></li>
									<li><label class="label"><input id="3" type="radio" name="radio" value="sia">Sia</label></li>
								</ul>
							</div>
						</div>
						<!--checkbox-->
						<div class="q-block">
							<div class="label">
								<label for="radio">Now, choose which of these bands/artists you would like to see live!</label>
							</div>
							<div>
								<ul>
									<li><label class="label"><input id="5" type="checkbox" name="live" value="foo-fighters">Foo Fighters</label></li>
									<li><label class="label"><input id="6" type="checkbox" name="live" value="killers">The Killers</label></li>
									<li><label class="label"><input id="7" type="checkbox" name="live" value="rihanna">Rihanna</label></li>
									<li><label class="label"><input id="8" type="checkbox" name="live" value="chemical-brothers">The Chemical Brothers</label></li>
								</ul>
							</div>
						</div>
						<!-- comment block-->
						<div class="q-block">
							<div>
								<div class="label">
									<label for="comments">Tell us shortly why you want to go to selected artists'/bands' concerts!</label>
								</div>
								<div class="input-field">
									<textarea name="comments"></textarea>
								</div>
							</div>
						</div>
					</div>
				</div>
				</div>
				<button id="submit" type="submit" >Submit</button>
			</div>
			<footer>Designed by Raminta Razgutė</footer>
		</form>
	</body>
</html>