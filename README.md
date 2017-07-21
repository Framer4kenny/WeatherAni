# WeatherAni
weatherAni

```
		.sun {
		  position: absolute;
		  top: 50%;
		  left: 50%;
		  width: 2.5em;
		  height: 2.5em;
		  margin: -1.25em;
		  background: currentColor;
		  border-radius: 50%;
		  /*background-image: url("")*/
		  box-shadow: 0 0 0 0.375em #fff;
		  /*z-index: -1;*/
		  animation: spin 12s infinite linear;
		}
		.cloud{
			position: absolute;
			width: 3.6875em;
			height: 3.6875em;
			left: 43.5%;
			top: 48.5%;
			margin: 1rem;
			border-radius: 50%;
			background: black; 
			box-shadow: 
				2rem 0rem 0 -0.475rem black,
				-2rem 0rem 0 -0.475rem black,
				0rem 0rem 0 0.375rem white,
				2rem 0rem 0 -0.175rem white,
				-2rem 0rem 0 -0.175rem white;
			/*z-index: 1;*/
		}
		@keyframes spin {
		  100% { transform: rotate(360deg); }
		}
    
```
