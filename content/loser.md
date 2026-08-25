+++
date = '2026-08-25T01:06:27+01:00'
draft = false
title = 'Loser'
+++

<style>
		body {
			width: 100%;
			height: 100%;
			overflow-y: auto;
			cursor: url('/profile.png') 16 16, auto;
			background: linear-gradient(45deg, #ff00cc, #3333ff, #00ff99, #ffff00);
			background-size: 600% 600%;
			animation: rainbow 10s linear infinite;
			font-family: 'Comic Sans MS', cursive, sans-serif;
			color: #fffc00;
			text-shadow: 2px 2px 5px #000;
			text-align: center;
			padding-top: 10vh;
			overflow-y: auto;
			min-height: 100vh;
		}
        @keyframes rainbow {
			0% { background-position: 0% 50%; }
			50% { background-position: 100% 50%; }
			100% { background-position: 0% 50%; }
		}
        h1 {
			font-size: 4rem;
			transform: rotate(-5deg);
			animation: spin 8s infinite alternate ease-in-out;
			margin-left: auto;
			margin-right: auto;
			width: 50%;
		}

		@keyframes pulse {
			0% { transform: scale(1); }
			50% { transform: scale(1.1); }
			100% { transform: scale(1); }
		}

		.confetti {
			position: fixed;
			width: 10px;
			height: 10px;
			background: #fff;
			animation: fall 3s infinite;
		}

		@keyframes fall {
			0% { transform: translateY(-10vh) rotate(0deg); }
			100% { transform: translateY(110vh) rotate(360deg); }
		}
</style>

<script>
for (let i = 0; i < 100; i++) {
			const confetti = document.createElement("div");
			confetti.classList.add("confetti");
			confetti.style.left = Math.random() * 100 + "vw";
			confetti.style.top = Math.random() * -100 + "vh";
			confetti.style.background = `hsl(${Math.random() * 360}, 100%, 50%)`;
			confetti.style.animationDuration = 2 + Math.random() * 3 + "s";
			confetti.style.opacity = Math.random();
			document.body.appendChild(confetti);
	}

	const trailImgURL = "/profile.png";
	document.addEventListener("mousemove", (e) => {
			const trail = document.createElement("img");
			trail.src = trailImgURL;
			trail.className = "cursor-trail";
			trail.style.left = `${e.clientX+20}px`;
			trail.style.top = `${e.clientY+20}px`;
			document.body.appendChild(trail);
			setTimeout(() => trail.remove(), 300);
	});
</script>


# HAHA! YOU THOUGHT IT WOULD BE THAT EASY?!?
## L BOZO

<iframe width="560" height="315" src="https://www.youtube.com/embed/QmfoscRuwFI?si=s-cDug8DZdzPUoaa&amp;controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
