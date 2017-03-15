# ImageCompressing
def ConversionNbBinaire (B) :
    n=0
    for i in range (8) :
        n+=B[i]*2**(7-i)
    return n
    
def ConversionListeBinaire (L) :
    D=[]
    for i in range (len(L)) :
        D.append(ConversionNbBinaire(L[i]))
    return D
    
