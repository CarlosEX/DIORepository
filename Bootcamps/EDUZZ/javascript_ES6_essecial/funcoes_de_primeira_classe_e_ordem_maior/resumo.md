# Funções de primeira classe e ordem maior
Essa é as funções mais utilizadas e um modelo "recomendado".

Exemplos:

`function getName(){
	return 'Carlos Antonio';
}

function logFn(fn){
	console.log(fn());
}

const logFnResult = logFn;
logFnResult(getName);
`
