var x = prompt("enter x", "")
var n = prompt("enter n", "")

function power(x, n){
	var res = x;
	for(i = 1; i < n; i++){
		res = res * x;
	}
	return res;
}

alert(power(x, n));

