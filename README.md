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

  
