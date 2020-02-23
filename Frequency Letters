import java.util.Scanner;
public class Main {

	public static void main (String args[]) {
	  int replacement2;int replacement1;char key1;char key2;int ans2;int ans1;int letter1=0;int letter2=0;int max1=0;int max2=0;int sw=0;int i=0;int j=0;char c[]={'a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z'};
	
		String Text="bf vjrhmsgseqlal, xkwjmxfvq tftdrkbk tdlg dfhog sl uhmglbfz dxlmwkk bk mzx kmmwq hx mzx xkwjmxfvq hx ewmlxjl gk ykgnhl gy dxlmwkk bf t ubhawklxpm law fwmzhv bk nkxv tk tf taw lh tkwtcbfz ueslkbutd vaizxjl xkwjmxfvq tftdrkbk bk uslww gg law ysvl mztl, bf tfr ybnxf llkwmua gy okamlxf esgynszw vwkltag dxlmwkk tfw uheuagsmahfl gy dxlmwkk huvmk obla ntjragy yjxinwgubwl ehjxgowk lawkw bk t uasksvlxjbkmav vbkmjbtnlbgg gy dxlmwkk mztl bk kgnyadr law lsfw ygk seehkm sed lsfhewl gy lasm dtfzmtyx xhj bflltfvw zaowg s lwvlbgg gy wgyealz esgynszw x l t sgv h skw mzx ehkm uhefgg, oaaew s i tfw p tjx jtjx dbcxobkx la wk gg sgv tf tjx law fgll vgfehf isbjl gy dxlmwkk mwkexv uazjtel gk vbyksizl sgv lk xw ml tfw xy skw mzx ehkm uhefgg jxhxsmk.";


			System.out.println(" ");
        System.out.println("******NOTICE******* ((**IF THE ENTERED SENTENCE HAS NOT BEEN FINISHED WITH (.) PLEASE ADD IT AT THE END OF SENTENCE**))");
            	System.out.println(" ");


	    char chr[]={' '};
	    char a[]={' '};
	    int d[]={0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0};
	    char b[]={' '};
	    int e[]={0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0};
	    
	    chr=Text.toCharArray();
	 
	   
	   
		System.out.println("Input_file.txt:");
		System.out.println(" ");
		System.out.println(chr);
			System.out.println(" ");
		System.out.println("Output:");
			System.out.println(" ");
		for(int z=0;chr[z]!='.';z++){
	
		    
		   for(int y=0;y<26;y++){
		       
		       if(chr[z]==c[y]){
		          
		            
		           if(sw==0){
		           a[i]=chr[z];
		           
		           d[y]++;
		        
		       
		           sw=1;
		               break;
		           }
		           else
		           {
		           b[j]=chr[z];
		           e[y]++;
		      
		        
		           sw=0;
		               break;
		           }
		           
		       }  //if
		       
		                   
		   }  //for
		   
		   
		    
		}   //for
		
	////  key1 Detection	
		for(int p=0;p<25;p++){
		    if(d[p]>max1){
		    max1=d[p];
		    letter1=p;}
		}
		ans1=letter1-4;
		    if(ans1<0)
		    ans1=ans1+26;
		    ans1=ans1%26;
		    key1=c[ans1];
		/////////////////////////////////////////
		
		///////key2 Detection
		for(int q=0;q<25;q++){
		    if(e[q]>max2){
		    max2=e[q];
		    letter2=q;}
		}
		ans2=letter2-4;
		    if(ans2<0)
		    ans2=ans2+26;
		    ans2=ans2%26;
		    key2=c[ans2];
		//////////////////////////////////////////////
		
			System.out.println("Key = "+ key1+key2); 
				System.out.println(" ");
			
			///////////////////////////////////////////////////
			//key replacement with charecters//
			sw=0;
			for(int z=0;chr[z]!='.';z++){
	
		    
		   for(int y=0;y<26;y++){
		       
		       if(chr[z]==c[y]){
		          
		            
		           if(sw==0){
		         
		        replacement1=y-ans1;
		        if (replacement1<0)
		        replacement1=replacement1+26;
		        replacement1=replacement1%26;
		        chr[z]=c[replacement1];
		           
		           
		        
		      
		           sw=1;
		               break;
		           }
		           else
		           {
		           replacement2=y-ans2;
		           if (replacement2<0)
		        replacement2=replacement2+26;
		        replacement2=replacement2%26;
		        chr[z]=c[replacement2];
		           
		          
		      
		        
		           sw=0;
		               break;
		           }
		           
		       }  //if
		       
		                   
		   }  //for
		   
		   
		    
		}   //for
		
		
			System.out.println(chr); 
		
	
	}
}
