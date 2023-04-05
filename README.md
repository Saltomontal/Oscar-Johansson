<!DOCTYPE html>
<html>
<head>
	<title>Delphi Dorm Party Archetype Quiz proudly presented by ChatGPT</title>
</head>
<body>
	<h1>Welcome to the Delphi Dorm Archetype Quiz - Raunchy Party Edition!</h1>
	<p>This quiz will place you into one of five archetypes of student personalities that live in a corridor at Delphi, Lund University. Answer the following ten questions honestly to find out which archetype you fit into. Have fun and enjoy getting to know more about the wilder side of student life at Lund!</p>
	<ol>
		<li>How often do you attend parties or go clubbing?</li>
		<ul>
			<li><input type="radio" name="question1" value="a">Every weekend, if not more</li>
			<li><input type="radio" name="question1" value="b">Only during exam periods as a stress-reliever</li>
			<li><input type="radio" name="question1" value="c">Whenever there's a themed party or food event</li>
			<li><input type="radio" name="question1" value="d">When there's a game night or movie marathon</li>
			<li><input type="radio" name="question1" value="e">Whenever a new adventure is calling</li>
		</ul>
		<li>What is your signature dance move at parties?</li>
		<ul>
			<li><input type="radio" name="question2" value="a">Twerking or any attention-grabbing move</li>
			<li><input type="radio" name="question2" value="b">The robot or something ironically nerdy</li>
			<li><input type="radio" name="question2" value="c">The funky chicken or something food-inspired</li>
			<li><input type="radio" name="question2" value="d">A group dance, like the Macarena or YMCA</li>
			<li><input type="radio" name="question2" value="e">Something acrobatic or risky</li>
		</ul>
		<li>What's your go-to party drink?</li>
		<ul>
			<li><input type="radio" name="question3" value="a">Shots, shots, shots!</li>
			<li><input type="radio" name="question3" value="b">A well-crafted cocktail or fine wine</li>
			<li><input type="radio" name="question3" value="c">A signature punch or home-brewed concoction</li>
			<li><input type="radio" name="question3" value="d">A classic beer or cider</li>
			<li><input type="radio" name="question3" value="e">Whatever's new and exotic</li>
		</ul>
		<li>What kind of music gets you on the dance floor?</li>
		<ul>
			<li><input type="radio" name="question4" value="a">Thumping EDM or techno</li>
			<li><input type="radio" name="question4" value="b">Indie, alternative, or underground tunes</li>
			<li><input type="radio" name="question4" value="c">A catchy tune everyone can sing along to</li>
			<li><input type="radio" name="question4" value="d">Classic party anthems</li>
			<li><input type="radio" name="question4"value="e">World music or something unusual</li>
</ul>
<li>What's your favorite pick-up line or ice breaker?</li>
<ul>
<li><input type="radio" name="question5" value="a">Something bold and provocative</li>
<li><input type="radio" name="question5" value="b">A witty pun or intellectual reference</li>
<li><input type="radio" name="question5" value="c">A food-related joke or compliment</li>
<li><input type="radio" name="question5" value="d">A friendly question or engaging topic</li>
<li><input type="radio" name="question5" value="e">A daring challenge or proposition</li>
</ul>
<li>What would you wear to a costume party at a Nation?</li>
<ul>
<li><input type="radio" name="question6" value="a">The most revealing or scandalous costume</li>
<li><input type="radio" name="question6" value="b">A subtle, clever costume with a nerdy twist</li>
<li><input type="radio" name="question6" value="c">A food-themed or chef-inspired outfit</li>
<li><input type="radio" name="question6" value="d">A classic costume with a flirty twist</li>
<li><input type="radio" name="question6" value="e">An adventurous or action-packed ensemble</li>
</ul>
<li>How do you usually end your night after a wild party?</li>
<ul>
<li><input type="radio" name="question7" value="a">Continuing the fun at an after-party or someone's room</li>
<li><input type="radio" name="question7" value="b">Unwinding with a good book or a late-night study session</li>
<li><input type="radio" name="question7" value="c">Cooking up some midnight snacks for the corridor</li>
<li><input type="radio" name="question7" value="d">Watching a movie or playing games with friends</li>
<li><input type="radio" name="question7" value="e">Going on a spontaneous late-night adventure</li>
</ul>
<li>What's your favorite party game or activity?</li>
<ul>
<li><input type="radio" name="question8" value="a">A provocative game of truth or dare or strip poker</li>
<li><input type="radio" name="question8" value="b">A challenging quiz or trivia contest</li>
<li><input type="radio" name="question8" value="c">A food-based competition or taste test</li>
<li><input type="radio" name="question8" value="d">A classic game like charades or Pictionary</li>
<li><input type="radio" name="question8" value="e">A daring physical challenge or scavenger hunt</li>
</ul>
<li>How would you handle a party crasher in your corridor?</li>
<ul>
<li><input type="radio" name="question9" value="a">Turn it into a corridor-wide party and invite even more people</li>
<li><input type="radio" name="question9" value="b">Engage them in a deep conversation about quantum physics</li>
<li><input type="radio" name="question9" value="c">Challenge them to a cook-off or food duel</li>
<li><input type="radio" name="question9" value="d">Invite them to join a game or watch a movie</li>
<li><input type="radio" name="question9" value="e">Take them on a wild adventure outside the corridor</li>
</ul>
<li>What's the craziest thing you've done at a party or club?</li>
<ul>
<li><input type="radio" name="question10" value="a">A wild dance-off or scandalous make-out session</li>
<li><input type="radio" name="question10" value="b">Presented an impromptu lecture or debate</li>
<li><input type="radio" name="question10" value="c">Started a food fight or eating contest</li>
<li><input type="radio" name="question10" value="d">Organized a flash mob or group dance</li>
<li><input type="radio" name="question10" value="e">Turned the party into a daring adventure or competition</li>
</ul>
</ol>
<button onclick="calculateResult()">Submit</button>
<div id="result"></div>
<script>
	function calculateResult() {
		let result = "";
		let aCount = 0;
		let bCount = 0;
		let cCount = 0;
		let dCount = 0;
		let eCount = 0;

		const question1 = document.querySelector('input[name="question1"]:checked').value;
		const question2 = document.querySelector('input[name="question2"]:checked').value;
		const question3 = document.querySelector('input[name="question3"]:checked').value;
		const question4 = document.querySelector('input[name="question4"]:checked').value;
		const question5 = document.querySelector('input[name="question5"]:checked').value;
		const question6 = document.querySelector('input[name="question6"]:checked').value;
		const question7 = document.querySelector('input[name="question7"]:checked').value;
		const question8 = document.querySelector('input[name="question8"]:checked').value;
		const question9 = document.querySelector('input[name="question9"]:checked').value;
		const question10 = document.querySelector('input[name="question10"]:checked').value;

		switch (question1) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question2) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question3) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question4) {
			case ""a":
				aCount++;
				break;
				case "b":
				bCount++;
				break;
				case "c":
				cCount++;
				break;
				case "d":
				dCount++;
				break;
				case "e":
				eCount++;
				break;
				}

		switch (question5) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question6) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question7) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question8) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question9) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		switch (question10) {
			case "a":
				aCount++;
				break;
			case "b":
				bCount++;
				break;
			case "c":
				cCount++;
				break;
			case "d":
				dCount++;
				break;
			case "e":
				eCount++;
				break;
		}

		if (aCount > bCount && aCount > cCount && aCount > dCount && aCount > eCount) {
			result = "The Wild Party Animal";
		} else if (bCount > aCount && bCount > cCount && bCount > dCount && bCount > eCount) {
			result = "The Intellectual Partier";
		} else if (cCount > aCount && cCount > bCount && cCount > dCount && cCount > eCount) {
			result = "The Foodie Reveler";
		} else if (dCount > aCount && dCount > bCount && dCount > cCount && dCount > eCount) {
			result = "The Social Gamer";
		} else {
			result = "The Daring Adventurer";
		}

		document.getElementById("result").innerHTML = 10;
	}
</script>
</body>
</html>
