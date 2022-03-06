//Questão 1

programa
{
	
	funcao inicio()
	{
		inteiro v[1000]
		inteiro i
		inteiro n
		inteiro mediana=0,x,m=0,md=0, chave=0, maior

       leia (n)

 
    	  para(i=0;i<n;i++){	
          	leia(x)
          	v[m]=x
          	v[i]=x
          }
          inteiro ordenado = 0 
          enquanto (ordenado==0){
          	ordenado =1
          	para (i=1;i<n;i++){
          		se(v[i] < v[i-1]){
          			inteiro aux= v[i]
          			v[i] = v[i-1] 
          			v[i-1]= aux
          			ordenado = 0          	
          			
          	}

          }
      }





      se(n%2==0){
      	md = (n/2)
      	mediana = (v[md]+v[md-1])/2

      }senao{
      	md=(n/2)
      	mediana=v[md]
      }

      escreva("\nmediana = ",mediana)


	

	} 
	

}
