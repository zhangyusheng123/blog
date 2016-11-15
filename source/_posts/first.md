---
title: first
date: 2016-11-15 17:30:
---
	canvas.onmouseout = function(e){
			e.preventDefault()
			isMouseDown =false;
			drawCanvasWidthMagnifter(false)
		}
		function drawCanvasWidthMagnifter(isShowMagnifier,point){
			cxt.clearRect(0,0,canvas.width,canvas.height);
			cxt.drawImage(image,0,0,canvas.width,canvas.height);
			if(isShowMagnifier ==true){
				darwMaginfier(point);
			}
		}
<div style="background:cyan;width:20px;height:50px;"></div>