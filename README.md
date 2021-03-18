# R.P.1._Montiel_Cruz_Joel_Gonzalo
identificar las Funciones, objetos, Clases, Métodos y Procedimientos correspondiente en el archivo Readme.md.

#IDENTIFICANDO FUNCION OBJETO

Los objetos en python son aquellas herramientas que utilizares en nuestra programacion aignandole un nombre com son

        menu=wx.MenuBar()           #Estamos declarando un objetos tipo MenuBar lo llamamos desde la lbreria WX
        creditos=wx.Menu()          #objeto Menu llamandose desde la libreria que de igal que este esta siendo declakrado como creditos que mas adelante sera llamado con self.
        contactos=wx.Menu()         #ogjeto Menu llamamos el objeto menu pero ahora lo almacenamos en la variable Contactos
        salir=wx.Menu()
         suma = wx.Button           #objeto Button almacenada en la variable Suma
        suma.Bind                   #objeto bind
        self.SetMenuBar(menu)       #objeto setmenuBar
        resta = wx.Button           #objeto Button almacenada en la variable RAESTA
        self.valor1 = wx.TextCtrl   #objeto Textctr1 llamada desde la libreia wx y almacenada en la varible valor1
         label1 = wx.StaticText     #Objeto StaticText   almacenada en la variable label

 
 
 
 
 
 
#IDENTIFICANDO FUNCION CLASS
Una clse es una instancia que contiene los objetos,metodos y atributos


def __init__(self):                #Tambien le llaman CONSTRUCTOR

class window (wx.Frame):           #class Window este es el objeto principal que contendra atributos  eventos ets
                                    que estallamando la clase FRAME cuyo apoyo es Un marco es una ventana cuyo tamaño y posición pueden (normalmente) ser cambiados por el                                           usuario.



#IDENTIFICANDO FUNCION METODO


       def creditos(self,event):                                            # El metodo CREDITOS este ejecuta un evento a realizar   
       salir=wx.MessageDialog(None, 'desarrollado por Ali Perez Gomez \     # seguido este contiene atributos al objeto MesaageDialog lo que le esta dando un nombre y tamaño al        n Colaborador 1: \n Colaborador 2:', 'Creditos',  style=wx.OK)          abojeto MessageDialogn  de jigual manera manda a llamar una variable
       salir.ShowModal()                                                    #objeto salir metodo ShowModal
         

       def salir(self,event):                                               # El metodo Salir
       salir=wx.MessageDialog(None, 'Saludos :,(','Salir', style=wx.OK)     #objeto MessageDialog con sus atributos
       self.Close(True)                                                     

       def contactar(self,event):                                           #metodo Contactar
       
       def paginas(self,event):#paginas python                              #metodo paginas
       
       def suma(self,event):#Suma                                           #metodo suma
        
       def resta(self,event):#Resta                                         #metodo resta
       
       
       
       
       
       
   #IDENTIFICANDO ATRIBUTOS  
   
        
        
        self.resultado.SetLabel(str(int (self.valor1.GetValue())*                                   #Atributo SetLabel
        int (self.valor2.GetValue())))                                                 
         
        resultado=wx.MessageDialog(None, 'su resultado es '+ str(int (self.valor1.GetValue())*      #Atributo MessageDialog este atributo le esta dando descripcion de tamaño de 
        int (self.valor2.GetValue())),'Resultado',style=wx.OK)                                       letra y de una variable de entrada
       
       
       
       self.valor1.SetLabel('Por Favor Ingrese el Primer Valor')                                   #Atributo SetLabel muestra un mensaje en la consola
       
         
app = wx.App()      # es una clase que arrnca el sistema de python
app.MainLoop()      #ejecuta los codijos
