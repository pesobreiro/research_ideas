#Variáveis
"sportSeason","name", "esc", "nFPN", "club", "assoc","gender","yearOfBirth","age", "ageDec","height","weight","bodyMass","wingSpan","wingSpanHeight","fatherHeight","motherHeight","adultHeight","adultHeightLevel", "t50mFree","t50mFree5.20m", "50mFreeVelocity","50mFreeStrokeRate","50mFreeStrokeLength","50mFreeSwimIndex","50mFreeTurnTime5.10m","50mFreeTurnIndex","SecoMI1Dist","SecoMI2Dist","SecoMI3Dist","LMAveDist","LMBestDistance","SECOMS1Dist","SECOMS2Dist","SECOMS3Dist","ULAverageDistance","ULBestDistance"

# Selecionadas
"age", "height", "weight", "wingSpan", "50mFreeTime", "50mFreeTime5.20", "50mFreeVelocity", "50mFreeStrokeRate", "50mFreeStrokeLength", "50mFreeSwimIndex", "50mFreeTurnTime5.10m", "50mFreeTurnIndex", "LMAveDist", "ULAveDist

age, height, weight, wingSpan, 50mFreeTime, 50mFreeTime5.20, 50mFreeVelocity, 50mFreeStrokeRate, 50mFreeStrokeLength, 50mFreeSwimIndex, 50mFreeTurnTime5.10m, 50mFreeTurnIndex, LMAveDist, ULAveDist


# Descrição

@50mFreeTime - Tempo total dos 50m Livres segundos
@50mFreeTime5.20 - Tempo retirado entre os 5 e 20 metros, o qual foi utilizado para calcular a velocidade de nado, a frequência gestual, a distância de ciclo e o índice de nado segundos
@50mFreeVelocity - Velocidade de nado calculada por 15/pelo variável anterior (tempo entre os 5 e 20m) m/s
@50mFreeStrokeRate - Frequência gestual, retirada com o cronômetro entre os 5m e 20m ciclos/min
@50mFreeStrokeLength - Distância de ciclo calculada por [(60xvelocidade)/frequência gestual] = [(60x@50mFreeVelocity)/@50mFreeStrokeRate] metros
@50mFreeSwimIndex - Índice de nado calculada por [velocidadexdistância de ciclo] = [@50mFreeVelocityx@50mFreeStrokeLength]
@50mFreeTurnTime5.10m - Tempo de viragem 5m antes da viragem + 10m depois da viragem segundos
@50mFreeTurnIndex - Índice de viragem calculado pela divisão entre o tempo de de nado (entre os 5m e 20m) e o tempo da viragem = @50mFreeTime5.20/@50mFreeTurnTime
As Variáveis que dizem SECO.MS1.Distância e as restantes são as tentativas que foram realizadas de força em seco. MS = membros superiores - lançamento da bola medicinal e MI = membros inferiores - salto horizontal, 1, 2 e 3 são as 3 tentativas.
Não as utilizei por isso deixei em portugues
LMAverageDistance - É a média da distância das 3 tentativas para os membros inferiores
LMBestDistance - Foi a melhor distância encontrada do atleta nas 3 tentativas possiveis nos membros inferiores
ULAverageDistance - É a média da distância das 3 tentativas para os membros superiores
ULBestDistance - Foi a melhor distância encontrada do atleta nas 3 tentativas possíveis nos membros superiores

As variáveis que utilizei para calcular a influência que têm no tempo total (@50mFreeTime) e no índice de nado (@50mFreeSwimIndex) foram as seguintes:   
- Age
- Height
- Weight
- Wigspan
-@50mFreeTime
-@50mFreeTime5.20
-@50mFreeVelocity
-@50mFreeStrokeRate
-@50mFreeStrokeLength
-@50mFreeSwimIndex
-@50mFreeTurnTime5.10m 
-@50mFreeTurnIndex
- LMAverageDistance 
- ULAverageDistance 
