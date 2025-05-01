'use client';
import './globals.css';
import { Montserrat } from 'next/font/google';

const montserrat = Montserrat({
  subsets: ['latin'],
  weight: ['400', '700'],
  variable: '--font-montserrat',
});

export default function Home() {
  return (
    <>
    <div className={`w-full h-screen justify-center items-center flex flex-col ${montserrat.className} `}>
      <p className='text-4xl font-bold'>Minha Pricesa💞</p>
      <p className='text-2xl font-light'>Linda por dentro e por fora!🌻</p>
    </div>
    <div className="fish">
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
    </div>
    <div className="fish">
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
      <div className="koiCoil"></div>
    </div>
    <div className="seaLevel"></div>
    </>
  );
}
