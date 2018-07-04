//---------------------------------------------------------------------------

#ifndef uRectangleFormH
#define uRectangleFormH
//---------------------------------------------------------------------------
#include <System.Classes.hpp>
#include <FMX.Controls.hpp>
#include <FMX.Forms.hpp>
#include <FMX.Controls.Presentation.hpp>
#include <FMX.Edit.hpp>
#include <FMX.StdCtrls.hpp>
#include <FMX.Types.hpp>
#include <FMX.Objects.hpp>
#include <complex>
#include <cmath>

typedef std::complex<double> dcomp;
//---------------------------------------------------------------------------
class TRectangleForm : public TForm
{
__published:	// IDE-managed Components
	TEdit *edtSheetWidth;
	TEdit *edtSheetHeight;
	TButton *btnCalc;
	TEdit *edtPieceHeight;
	TEdit *edtPieceWidth;
	TLabel *Label1;
	TLabel *Label2;
	TLabel *Label3;
	TLabel *Label4;
	TImage *Image1;
	TEdit *edtSheetTrim;
	TLabel *Label5;
	void __fastcall btnCalcClick(TObject *Sender);
private:	// User declarations
public:		// User declarations
	__fastcall TRectangleForm(TComponent* Owner);
    double getRealCubicRoots(double cA, double cB, double cC, double cD);
	double solveQuartic(double qA, double qC, double qD, double qE, double sheetHeight);
	double solveOneRealCubicRoot(double cA, double cB, double cC, double cD, double cH);
	dcomp solveFirstComplexCubicRoot(double cA, double cB, double cC, double cD, double cH);
	dcomp solveSecondComplexCubicRoot(double cA, double cB, double cC, double cD, double cH);
	double solveFirstRealCubicRoot(double cA, double cB, double cC, double cD, double cH);
	double solveSecondRealCubicRoot(double cA, double cB, double cC, double cD, double cH);
	double solveThirdRealCubicRoot(double cA, double cB, double cC, double cD, double cH);
	dcomp solveFirstQuarticRoot(dcomp qP, dcomp qQ, dcomp qR);
	dcomp solveSecondQuarticRoot(dcomp qP, dcomp qQ, dcomp qR);
	dcomp solveThirdQuarticRoot(dcomp qP, dcomp qQ, dcomp qR);
	dcomp solveFourthQuarticRoot(dcomp qP, dcomp qQ, dcomp qR);
	double posOrNegCubeRoot(double base);
	dcomp posOrNegSquareRoot(double base);
	dcomp complexSquareRoot(dcomp base);
    //double calculateQC(double sheetWidth, double sheetHeight, double pieceWidth);
};
//---------------------------------------------------------------------------
extern PACKAGE TRectangleForm *RectangleForm;
//---------------------------------------------------------------------------
#endif
