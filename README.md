# Homework1
fun main() {
val alfabet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
println(alfabet)
val temp: CharArray = alfabet.toCharArray()
println(temp.contentToString())
println(temp.size)temp.forEachIndexed {index, temp -> println("$index - $temp")}
println(temp.filterIndexed {index, temp -> index % 2 != 0 })

val alfabetlist = listOf('A','B','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z')
println(alfabetlist.filterIndexed {index, _ -> index % 2 != 0 })
}
