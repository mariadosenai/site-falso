/* 
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/ClientSide/javascript.js to edit this template
 */

document.getElementById('cadastroForm').addEventListener('submit', function(event) {
    event.preventDefault();  // Previne o envio real do formulário
    console.log('Formulário submetido!');
    
    const nome = document.getElementById('nome').value;
    const cpf = document.getElementById('cpf').value;
    const cidade = document.getElementById('cidade').value;
    const estado = document.getElementById('estado').value;
    
    if (nome && cpf && cidade && estado) {
        document.getElementById('message').textContent = "Erro! Sua conta bancária foi acessada, você tem atualmente $12,00 reais, parabéns!! Agraças ao seu CPF;)";
        document.getElementById('message').style.color = 'red';
    } else {
        document.getElementById('message').textContent = "Por favor, preencha todos os campos.";
    }
});