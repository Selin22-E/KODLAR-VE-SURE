# KODLAR-VE-SURE
#include <stdio.h>
#include <time.h>
int main() {
clock_t start = clock();
printf("Merhaba MIS, algoritma ve programlama\n");
clock_t end = clock();
double time_spent = (double)(end - start) /
CLOCKS_PER_SEC;
printf("C işlem süresi: %f saniye\n", time_spent);
return 0;
}
Merhaba MIS,algoritma ve programlama
C işlem süresi:0.000025 saniye


using System;
using System.Diagnostics;
class Program
{
static void Main()
{
Stopwatch stopwatch = new Stopwatch();
stopwatch.Start();
Console.WriteLine("Merhaba MIS, algoritma ve programlama dersi başladı");
stopwatch.Stop();
Console.WriteLine($"C# işlem süresi: {stopwatch.Elapsed.TotalSeconds} saniye");
}
}

Merhaba MIS,algoritma ve programlama dersi başladı
C# işlem süresi 0.0474452 saniye


package main
import (
"fmt"
"time"
)
func main() {
start := time.Now()
fmt.Println("Merhaba MIS, algoritma ve programlama")
elapsed := time.Since(start)
fmt.Printf("Go işlem süresi: %s saniye\n", elapsed)
}

Merhaba MIS, algoritma ve programlama
Go işlem süresi: 51.731µs saniye

use std::time::Instant;
fn main() {
let start = Instant::now();
println!("Merhaba MIS, algoritma ve programlama");
let duration = start.elapsed();
println!("Rust işlem süresi: {:?}", duration);
}
Merhaba MIS, algoritma ve programlama
Rust işlem süresi: 10.351µs
start = Time.now
puts "Merhaba MIS, algoritma ve programlama"
finish = Time.now
puts "Ruby işlem süresi: #{finish - start} saniye"


Merhaba MIS, algoritma ve programlama
Ruby işlem süresi: 1.6861e-05 saniye


use Time::HiRes qw(time);
my $start = time();
print "Merhaba MIS, algoritma ve programlama\n";
my $end = time();
printf "Perl işlem süresi: %f saniye\n", $end - $start;


Merhaba MIS, algoritma ve programlama
Perl işlem süresi: 0.000015 saniye

import time
start = time.time()
print("Merhaba MIS, algoritma ve programlama
dersi başladı")
end = time.time()
print(f"Python işlem süresi: {end - start} saniye")

Merhaba MIS,algoritma ve programlama dersi başladı
Python işlem süresi:2.14576721191406 25e-05 saniye
