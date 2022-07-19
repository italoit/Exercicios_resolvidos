//# Exercicios_resolvidos
//Mostrando meu desempenho ao longo das atividades do curso de programação para iniciantes.
package Atividade;

import java.util.Locale;

import java.util.Scanner;

public class questao_6 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		// 3.0 4.0 5.2
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);
		double A, B, C;
		double ART;
		double ARC;
		double ARTP;
		double ARR;
		double ARQ;
		double pi = 3.14159;
		A = sc.nextDouble();
		B = sc.nextDouble();
		C = sc.nextDouble();
		ART = (A * C) / 2;
		ARC = pi * Math.pow(C, 2.0);
		ARTP = (A + B) * C / 2.0;
		ARQ = B * B;
		ARR = A * B;
		System.out.printf("TRIÂNGULO:%.3f%nCÍRCULO:%.3f%nTRAPEZIO:%.3f%nQUADRADO:%.3f%nRETÂNGULO:%.3f%n", ART, ARC,
				ARTP, ARQ, ARR);

		sc.close();
	}

}
