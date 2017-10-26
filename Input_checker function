void input_checker(string input) // assignment or operation
{
	int flag=0; // flag=0 => assignemnt flag=1 => operation
    string matrix_name;
	matrix_name=input.substr(0,matrix_name.find('='));
	matrix_name=matrix_name.substr(0,matrix_name.find(' ')) ;
    string matrix;
	matrix=input.substr(input.find('=')+1,(input.length()-input.find('='))-1);
		 int index = memory_check(matrix_name);
	   
	   if((input.find('{')!=-1)&&(input.find('}')!=-1)){
flag=0;
 create_matrix(index,matrix,matrix_name); 

		}
		else if((matrix.find("+")!=-1)||(matrix.find("-")!=-1)||(matrix.find("/")!=-1)||(matrix.find("*")!=-1)||(matrix.find("^")!=-1))
		{
			flag=1;
			if(index=-1)
				memory.push_back(temp);
			if(matrix.find("+")!=-1)
			{
				string Variable1= matrix.substr(0,matrix.find('+')) ;
				string variable2= matrix.substr(matrix.find('+'),(matrix.length()-matrix.find('+'))-1);

                int index1=memory_check(variable1);
				int index2=memory_check(variable2);

if(index!=-1)
memory[index]=memory[index1]+(memory[index2]) ;
else
	memory.back=memory[index1]+(memory[index2]) ;
}
			else if(matrix.find("-")!=-1)
			{
				string Variable1= matrix.substr(0,matrix.find('-')) ;
				string variable2= matrix.substr(matrix.find('-'),(matrix.length()-matrix.find('-'))-1);
				int index1=memory_check(variable1);
				int index2=memory_check(variable2);

if(index!=-1)
memory[index]=memory[index1]-(memory[index2]) ;
else
	memory.back=memory[index1]-(memory[index2]) ;
}
			else if(matrix.find("*")!=-1)
			{
				string Variable1= matrix.substr(0,matrix.find('*')) ;
				string variable2= matrix.substr(matrix.find('*'),(matrix.length()-matrix.find('*'))-1);
                int index1=memory_check(variable1);
				int index2=memory_check(variable2);

if(index!=-1)
memory[index]=memory[index1]*(memory[index2]) ;
else
	memory.back=memory[index1]*(memory[index2]) ;
}

			else if(matrix.find("/")!=-1)
			{
				string Variable1= matrix.substr(0,matrix.find('/')) ;
				string variable2= matrix.substr(matrix.find('/'),(matrix.length()-matrix.find('/'))-1);

int index1=memory_check(variable1);
int index2=memory_check(variable2);

if(index!=-1)
memory[index]=memory[index1]/(memory[index2]) ;
else
	memory.back=memory[index1]/(memory[index2]) ;
}
			else if(matrix.find("^")!=-1)
			{
				string Variable1= matrix.substr(0,matrix.find('^')) ;
	
int index1=memory_check(variable1);
				

if(index!=-1)
memory[index]=^(memory[index1]) ;
else
	memory.back=(^memory[index1]) ;
}
}
		else cout<<"invalid input"<<endl ;
}
