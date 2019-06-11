# Stwórzcie w pokoju klaster przy użyciu docker swarma zdeplojujcie wcześniej uzytą aplikację jako 
# stack z redisem. 

# Przy użyciu dowolnego narzędzia do benchamrku  np.
for i in {1..3}; curl -s -w "%{time_total}\n" -o /dev/null http://localhost:8080/ 
# przetestuj wydajność swojego klastra. 