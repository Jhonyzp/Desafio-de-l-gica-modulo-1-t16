function solucao(lista) {
  //seu codigo aqui
  const input = "1 2 3 4";
   main(input);
    
  function solucao(input) {
    let total = 0;
    for (let i = 0; i < lista.length; i++) {
        total += lista[i];
    }
    console.log(total);
}
    function main(input) {
    const valores = input.split(" ").map(Number);
    const total = solucao(valores);
}
}
