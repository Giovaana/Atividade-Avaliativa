# Atividade-Avaliativa
Valendo 2 pontos

01- Alternativa D.

02-

  a) 
  void main(){
  int a=1;
  int b=2;
  String c= 'Olá Mundo';

  print(a);
  print(b);
  print(c);
}

 b)
  
void main(){ 
  num();
}
void num(){ 
  for(int i=1; i<=10;i++){
   print (i); 
  } 
}

 c)
  void main(){ 
  int a=50;
  num(a);
}
void num(int c){ 
  for(int i=1; i<=c;i++){
   print (i); 
  } 
}

d)
void main(){ 
  int a=4;
  num(a);
}
 void num(int c){ 
  int soma=0;
  for(int i=1; i<=c;i++){
   print (i); 
    soma=soma+i;
  }
    print(soma);
}

e)
  void main(){ 
  Arara a= new Arara('Blue',2,1.0);
  a.Comer();
  a.Andar();
}
class Arara{
   String nome;
   int idade;
   double peso;
   
 Arara(this.nome,this.idade,this.peso); 
  
 void Comer(){
  print('$nome encheu a barriga!');
 }
 void Andar(){
  print('$nome se locomoveu!');
 }
}

---------------------------------------------- ATIVIDADE PARA PONTO -------------------------------------------------


void main() {

Banco b= new Banco('Eu',123,'Normal', 1000.00);
  print('----------------BANCO--------------------');
  b.Criar();
  print('-----------------------------------------');
  b.Deposito(50.00);
  print('-----------------------------------------');
  b.Saque(100.00);
  print('-----------------------------------------');
  b.Saldo();
  print('-----------------------------------------');
  b.Transferencia(100.00);
}

class Banco{
  String nome;
  int numc;
  String tipo;
  double saldoatual;
  double valordep;
  double valorsaque;
  double transferencia;
  
  Banco(this.nome, this.numc, this.tipo,this.saldoatual);
  
  void Criar(){
    print('$nome sua conta foi criada!');
    print('Seu saldo atual é de: $saldoatual');
  }
  void Saldo(){
   print('Saldo atual: ${this.saldoatual}'); 
  }
  void Deposito(double a){
    this.saldoatual=this.saldoatual+a; 
    print('Depósito realizadoo com sucesso!');
    print('Seu saldo atual é de: ');
    print(saldoatual);
  }
   void Saque(double b){
     if(saldoatual>=b){
    this.saldoatual=this.saldoatual-b;
     print('Saque realizadoo com sucesso!');
     print('Seu saldo atual é de: ');
    print(saldoatual);
     }
     else{
       print('Saldo insuficiente');
     }
   }
  void Transferencia(double c){
    print('Transferência realizada com sucesso!');
    print('Seu saldo atual é de: ');
    print(saldoatual-c);
  }
}












  
